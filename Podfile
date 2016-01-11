source 'https://github.com/CocoaPods/Specs.git'

xcodeproj 'AeroGearSyncClient.xcodeproj'
platform :ios, '8.0'
use_frameworks!

target 'AeroGearSyncClientJsonPatch' do
	pod 'Starscream', :git => 'https://github.com/daltoniam/Starscream'
	pod 'AeroGearSyncJsonPatch', :git => 'https://github.com/corinnekrych/aerogear-ios-sync', :branch => 'podspec.fixes'
end

target 'AeroGearSyncClientDiffMatchPatch' do
	pod 'Starscream', :git => 'https://github.com/daltoniam/Starscream'
	pod 'AeroGearSyncDiffMatchPatch', :git => 'https://github.com/corinnekrych/aerogear-ios-sync', :branch => 'podspec.fixes'
end

target 'AeroGearSyncClientTests' do
    pod 'Starscream', :git => 'https://github.com/daltoniam/Starscream'
	pod 'AeroGearSyncJsonPatch', :git => 'https://github.com/corinnekrych/aerogear-ios-sync', :branch => 'podspec.fixes'
end
