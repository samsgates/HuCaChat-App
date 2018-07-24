# Uncomment this line to define a global platform for your project
use_frameworks!
platform :ios, '8.0'

def demo_chat_frameworks
    #start - add firebase
    pod 'Firebase'
    pod 'Firebase/Database'
    pod 'Firebase/Auth'
    pod 'Firebase/Storage'
    pod 'Kingfisher'
    #end
    
    #start - add google adMob
    pod 'Firebase/AdMob'
    #end
    
    #start - google analytics
    pod 'GoogleAnalytics'
    pod 'Firebase/Core'
    #end
    
    pod 'EZAlertController' #lib message
    
    #start - add fabric and login twitter
    pod 'Fabric'
    pod 'Crashlytics'
    pod 'TwitterKit'
    #end
    
    #Nifty cloud
    pod 'NCMB', :git => 'https://github.com/NIFTYCloud-mbaas/ncmb_ios.git'
    #end
    
    #start - tracking user in MAP
    pod 'GoogleMaps'
    pod 'Socket.IO-Client-Swift'
    #end
    
    #start - add pod support movie function
    pod 'Alamofire'
    #pod 'PageMenu', '~> 1.2.9'
    pod 'youtube-parser'
    #end
    
    #start - add pod support music function
    pod 'FMDB'
    #end
    
    #start - add add support layout UI
    pod 'SnapKit', '~> 4.0.0'
    #end
end

target 'HuCaChat_Dev' do
    demo_chat_frameworks
end

target 'HuCaChat_Release' do
    demo_chat_frameworks
end

#post_install do |installer|
#    installer.pods_project.targets.each do |target|
#        target.build_configurations.each do |config|
#            config.build_settings['SWIFT_VERSION'] = '3.0'
#        end
#    end
#end

