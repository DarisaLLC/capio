# Uncomment this line to define a global platform for your project
# platform :ios, '9.0'

target 'capio' do
  # Comment this line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  pod 'MotionAnimation', :git => 'https://github.com/ronanamsterdam/MotionAnimation', :branch => 'refac/swift5'
  pod 'ElasticTransition', :git => 'https://github.com/ronanamsterdam/ElasticTransition.git', :branch => 'refac/swift5'
  pod 'JQSwiftIcon', :git => 'https://github.com/ronanamsterdam/JQSwiftIcon.git', :branch => 'refac/swift5'
  pod 'BRYXBanner'
  pod 'ScalePicker', :git => 'https://github.com/ronanamsterdam/ScalePicker.git', :branch => 'refac/swift5'

  pod 'CariocaMenu', :git => 'https://github.com/ronanamsterdam/cariocamenu.git', :branch => 'refac/swift5'

  pod 'RxSwift'
  pod 'RxCocoa'


  # Pods for capio

  target 'capioTests' do
    inherit! :search_paths
    # Pods for testing
    pod 'RxBlocking'
    pod 'RxTest'
  end

  target 'capioUITests' do
    inherit! :search_paths
    # Pods for testing
  end

  post_install do |installer|
    installer.pods_project.targets.each do |target|
        if ['BRYXBanner'].include? target.name
            target.build_configurations.each do |config|
                config.build_settings['SWIFT_VERSION'] = '5.0'
            end
        end
    end
  end

end
