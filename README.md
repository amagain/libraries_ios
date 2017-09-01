# iOS Libraries

## Introduction

This is a collection of iOS libraries I often use in iOS app development.

## Usage

First, clone this repo in a path like ~/libraries-ios

```
git clone https://github.com/fmo91/libraries_ios.git ~/libraries-ios
```

Then, in your podfile, write some of the following lines:

```ruby
pod 'Alamofire', :path => '~/libraries_ios/Alamofire'
pod 'AFDateHelper', :path => '~/libraries_ios/DateHelper'
pod 'DequeuableRegistrable', :path => '~/libraries_ios/DequeuableRegistrable'
pod 'IQKeyboardManagerSwift', :path => '~/libraries_ios/IQKeyboardManager'
pod 'Kingfisher', :path => '~/libraries_ios/Kingfisher'
pod 'ObjectMapper', :path => '~/libraries_ios/ObjectMapper'
pod 'RxSwift', :path => '~/libraries_ios/RxSwift'
pod 'RxCocoa', :path => '~/libraries_ios/RxSwift'
pod 'SVProgressHUD', :path => '~/libraries_ios/SVProgressHUD'
pod 'SnapKit', :path => '~/libraries_ios/SnapKit'
```