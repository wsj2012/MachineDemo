source 'https://github.com/wsj2012/MiniShare.git'
source 'https://github.com/CocoaPods/Specs.git'
#source 'http://git-ma.paic.com.cn/ToaApp/yzt-pod-master.git'

workspace 'MachineDemo.xcworkspace'

platform :ios, '8.0'
use_frameworks!

def shared_pods
    pod 'SnapKit'
end

target 'MachineDemo' do
    project 'MachineDemo.xcodeproj'
    shared_pods
end

target 'Example' do
    project 'Example/Example.xcodeproj'
    shared_pods
end
