# WWDC
**A command-line interface for accessing WWDC session content**

[ASCIIwwdc](http://asciiwwdc.com) provides searchable full-text transcripts of WWDC content. `wwdc` builds on its API, [which is documented in the project's README](https://github.com/mattt/asciiwwdc.com#README).

> As a CLI aficionado, you should definitely check out [Nomad](http://nomad-cli.com/), a world-class command line utilities for iOS development.

## Installation

```bash
$ gem install wwdc
```

## Usage

```bash
$ wwdc info 228

    228: "A Look Inside Presentation Controllers"
    iOS 8 brings you powerful new means of presenting content within your apps. Hear how presentation controllers were leveraged by UIKit to give you fine grain control using new alert and searching APIs. Dive deep into how presentation controllers work and how you can use them to present content within your app in exciting new ways.

$ wwdc info 228 2013

    228: "Hidden Gems in Cocoa and Cocoa Touch"
    Learn from the experts about the Cocoa and Cocoa Touch classes you may not even know exist, as well as some very obscure but extremely valuable classes that are favorites of the presenters.

$ wwdc open 228

    # Opens browser to Apple Developer page with links to slides and video for this year

$ wwdc open 228 2013

    # Opens browser to Apple Developer page with links to slides and video for 2013

$ wwdc search UIView

    203: "What’s New in Cocoa Touch"
    UIView property called tintColor. So, Andy talked about the fact that we've taken the tintColor concept and hoisted it all the way up to UIView, right.

    ...
```

## Contact

Mattt Thompson

- http://github.com/mattt
- http://twitter.com/mattt
- m@mattt.me

## License

WWDC is available under the MIT license. See the LICENSE file for more info.

All content copyright © 2013 Apple Inc. All rights reserved.
