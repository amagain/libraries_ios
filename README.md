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
pod 'Alamofire', :path => '~/libraries-ios/Alamofire/Alamofire.podspec'
pod 'AFDateHelper', :path => '~/libraries-ios/DateHelper/AFDateHelper.podspec'
pod 'DequeuableRegistrable', :path => '~/libraries-ios/DequeuableRegistrable/DequeuableRegistrable.podspec'
pod 'IQKeyboardManagerSwift', :path => '~/libraries-ios/IQKeyboardManager/IQKeyboardManagerSwift.podspec.json'
pod 'Kingfisher', :path => '~/libraries-ios/Kingfisher/Kingfisher.podspec'
pod 'ObjectMapper', :path => '~/libraries-ios/ObjectMapper/ObjectMapper.podspec'
pod 'RxSwift', :path => '~/libraries-ios/RxSwift/RxSwift.podspec'
pod 'RxCocoa', :path => '~/libraries-ios/RxSwift/RxCocoa.podspec'
pod 'SVProgressHUD', :path => '~/libraries-ios/SVProgressHUD/SVProgressHUD.podspec'
pod 'SnapKit', :path => '~/libraries-ios/SnapKit/SnapKit.podspec'
```