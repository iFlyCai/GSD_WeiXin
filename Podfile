# Uncomment the next line to define a global platform for your project
 platform :ios, '15.6'

target 'GSD_WeiXin(wechat)' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for GSD_WeiXin(wechat)
  pod "MLEmojiLabel"
  post_install do |installer|
    installer.pods_project.targets.each do |target|
      target.build_configurations.each do |config|
        config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '15.6'
      end
    end
  end
  target 'GSD_WeiXin(wechat)Tests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'GSD_WeiXin(wechat)UITests' do
    # Pods for testing
  end

end
