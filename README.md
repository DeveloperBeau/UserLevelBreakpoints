# My Breakpoints

- All Exceptions
- All Objective-C Exceptions
- All C++ Exceptions
- Swift Error
- Test Failure
- OpenGL ES Error
- Automatic LLDB `@import UIKit` and `@import Foundation`
- Automatic LLDB `@import Cocoa` and `@import Foundation`
- Unsatisfiable AutoLayout Constraints
- KVO Deallocate
- CGPostError
- NSData Reinitialization
- UIApplicationMain ([Reveal](http://revealapp.com) framework injection)

Read more about Automatic LLDB import of `UIKit` et al here: http://furbo.org/2015/05/11/an-import-ant-change-in-xcode/  
Thanks Steve, Natasha for misc https://gist.github.com/forbze/919c7fced35f6ff59cbd  
Thanks [@vlas-voloshin](https://github.com/vlas-voloshin) for `KVO`  
Thanks [Reveal](revealapp.com)  

### Reveal

The Reveal breakpoint is as described in the [Reveal Integration Guide](http://support.revealapp.com/kb/getting-started/load-the-reveal-server-via-an-xcode-breakpoint).

Since *Reveal 5* you need to install the debugger commands before using the breakpoint.

## Install

Just clone this gist:

```
git clone https://gist.github.com/5c1ede17f8cec1f8b529.git ~/Library/Developer/Xcode/UserData/xcdebugger/
```

Or place `Breakpoints_v2.xcbkptlist` in `~/Library/Developer/Xcode/UserData/xcdebugger/` manually.
