source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'
use_frameworks!

target ‘swift-remote-push-notification’ do


pod 'Fabric'

pod 'Firebase/Core'

pod 'Firebase/Messaging'

pod 'Firebase/Crash'

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '3.0'
    end
  end
end