# InStatDownloadButton 

[![Twitter](https://img.shields.io/badge/twitter-@JiromTomson-blue.svg?style=flat
)](https://twitter.com/JiromTomson)
[![CI Status](https://travis-ci.org/tularovbeslan/InStatDownloadButton.svg?branch=master)](https://travis-ci.org/tularovbeslan@gmail.com/InStatDownloadButton)
[![Version](https://img.shields.io/cocoapods/v/InStatDownloadButton.svg?style=flat)](https://cocoapods.org/pods/InStatDownloadButton)
![iOS 10.0+](https://img.shields.io/badge/iOS-10.0%2B-red.svg)
![Swift 5](https://img.shields.io/badge/Swift-5-orange.svg)
[![License](https://img.shields.io/cocoapods/l/InStatDownloadButton.svg?style=flat)](https://cocoapods.org/pods/InStatDownloadButton)
[![Platform](https://img.shields.io/cocoapods/p/InStatDownloadButton.svg?style=flat)](https://cocoapods.org/pods/InStatDownloadButton)

![IMG_1268 TRIM 2019-03-12 16_27_11](https://user-images.githubusercontent.com/4906243/54244155-65377b80-453c-11e9-8303-d24289b855b8.gif)


## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Customize

```
func setupProgressView() {

    downloadButton.progressView.startAngle = -90
    downloadButton.progressView.progressThickness = 0.2
    downloadButton.progressView.trackThickness = 0.6
    downloadButton.progressView.clockwise = true
    downloadButton.progressView.gradientRotateSpeed = 2
    downloadButton.progressView.roundedCorners = false
    downloadButton.progressView.glowMode = .forward
    downloadButton.progressView.glowAmount = 0.9
    downloadButton.progressView.stopColor = UIColor.red.cgColor
    downloadButton.progressView.set(colors: UIColor.cyan, UIColor.orange)
}
```

```
func setupIndicatorView() {

    downloadButton.indicatorView.startAngle = -90
    downloadButton.indicatorView.progressThickness = 0.2
    downloadButton.indicatorView.trackThickness = 0.6
    downloadButton.indicatorView.gradientRotateSpeed = 2
    downloadButton.indicatorView.roundedCorners = false
    downloadButton.indicatorView.glowMode = .forward
    downloadButton.indicatorView.glowAmount = 0.9
    downloadButton.indicatorView.set(colors: UIColor.cyan)
    downloadButton.indicatorView.trackColor = .black
}
```
## Requirements

## Installation

InStatDownloadButton is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'InStatDownloadButton'
```

# Author

Beslan Tularov | <a href="url"><img src="https://user-images.githubusercontent.com/4906243/54856729-037dcb00-4d0d-11e9-9d6f-8a5b8e316ff8.png" height="15"> </a> [@JiromTomson](https://twitter.com/JiromTomson)

## License

```
MIT License

Copyright (c) 2018 Beslan Tularov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
