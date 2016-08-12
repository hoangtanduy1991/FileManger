# Video Uploader

## Requirements
 Demo redmine 
* Platform: iOS
* Supported iOS versions: 8.0+
* Apple accounts/credentials: N/A
* Existing provisioning profiles: N/A

## Dependencies

* Service/API documentation: N/A
* Profile/account/platform credentials: 
* Flowcharts, documents: https://redmine.codecomplete.jp/projects/ios_videouploader/files

### General Assets

* Icons of supported sizes: @1x, @2x
* Splash screens of supported sizes: all size
* Screenshots in correct sizes, in required languages: N/A
* List of supported devices and OS versions: iOS8.0+, iphone 4 to iphone 6S.

### Apple App Store

* iTunes Connect Account access: N/A
* Company/Entity Name: CodeComplete K.K.
* Bundle id / SKU: com.mytrax.uploadvideo1
* App store distribution provision profile: N/A

### Special steps of compilation
##CocoaPods
1. Setup library is using in project through [CocoaPods](http://cocoapods.org). If you have not installed CocoaPods, install CocoaPods by running the command:

		$ gem install cocoapods
		$ pod setup

    Depending on your system settings, you may have to use `sudo` for installing `cocoapods` as follows:

		$ sudo gem install cocoapods
		$ pod setup
        
2. Then run the following command:
	
		$ pod install

##Crashlytics
1. Please setup crashlytics follow instructions:
   https://docs.fabric.io/ios/fabric/getting-started.html

2. Open up `*.xcworkspace` with Xcode and start building project.
