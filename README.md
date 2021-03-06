# ARASCIISwizzle

[![Build Status](https://travis-ci.org/dblock/ARASCIISwizzle.png?branch=master)](https://travis-ci.org/dblock/ARASCIISwizzle)
[![Version](http://cocoapod-badges.herokuapp.com/v/ARASCIISwizzle/badge.png)](http://cocoadocs.org/docsets/ARASCIISwizzle)
[![Platform](http://cocoapod-badges.herokuapp.com/p/ARASCIISwizzle/badge.png)](http://cocoadocs.org/docsets/ARASCIISwizzle)

ASCII-art all the things. Transforms all UIImageView's into ASCII art and replaces all fonts with Courier.
Built for the [Artsy.net](http://artsy.net) March 2014 Hackathon.
Combine with [DRKonamiCode](https://github.com/objectiveSee/DRKonamiCode) and you're in business!

## Demo

![](Demo/Screenshots/swizzle-portrait-of-a-lady.gif)

[Portrait of a Lady, Rogier Van Der Weyden](https://artsy.net/artwork/rogier-van-der-weyden-portrait-of-a-lady-1), courtesy of the National Gallery of Art, Washington D.C., via Artsy.net

## Usage

``` objc
#import <ARASCIISwizzle/UIFont+ASCII.h>
#import <ARASCIISwizzle/UIImageView+ASCII.h>

- (void)toggle
{
    UIFont.ascii = ! UIFont.ascii;
    UIImageView.ascii = ! UIImageView.ascii;
}
```

## Installation

ARASCIISwizzle is available through [CocoaPods](http://cocoapods.org), to install it simply add the following line to your Podfile:

    pod "ARASCIISwizzle"

## Testing

Try it out with CocoaPods also,

    pod try "ARASCIISwizzle"

## Credits

* [Creating ASCII Art from UIImage](http://weakreference.wordpress.com/2010/11/17/ios-creating-an-ascii-art-from-uiimage)
* [Creating a UIImage from Text](http://stackoverflow.com/questions/2765537/how-do-i-use-the-nsstring-draw-functionality-to-create-a-uiimage-from-text)
* [Resizing a UIImage](http://stackoverflow.com/questions/7645454/resize-uiimage-by-keeping-aspect-ratio-and-width)

## Copyright & License

ARASCIISwizzle is (c) [Artsy Inc.](http://artsy.net), available under the MIT license.

See the [LICENSE](LICENSE) file for more information.

