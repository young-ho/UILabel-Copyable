UILabel+Copyable
===

A simple UILabel category meant to add copy functionality to it.

# Features
- Supports Interface Builder
- Supports long press gesture
- Allows enable/disble the copy feature
- Works with all UILabel objects already in your project

# Installation

### CocoaPods
The easiest way of installing UILabel+Copyable is via [Cocoapods](http://cocoapods.org/). 

```
pod 'UILabel+Copyable', '~> 1.0.0'
```

### Old-fashioned way

- Add `UILabel+Copyable.h` and `UILabel+Copyable.m` to your project.
- `#import "UILabel+Copyable.h"` where you want to use the control.
- These files require **ARC**.

# Usage

Just import the category header: `#import "UILabel+Copyable.h"` and then set the `copyingEnabled` property to `YES`:

```  objective-c
UILabel *label = [[UILabel alloc] initWithFrame:CGRectMake(0, 0, 100, 30)];
label.copyingEnabled = enabled;
[self.view addSubview:label];
```

Included is a demo project showing how to use it from a storyboard.

![UILabel+Copyable](https://raw.githubusercontent.com/alexandreos/UILabel-Copyable/screenshots/screenshot.png)

# Change log
* version 1.0.0
* Initial release

# License

UILabel+Copyable is licensed under the terms of the MIT License. Please see the [LICENSE](LICENSE.md) file for full details.
