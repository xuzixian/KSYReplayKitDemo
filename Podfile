platform :ios, '7.0'
inhibit_all_warnings!
use_frameworks!

target 'KSYRKUploadExt' do
	pod 'GPUImage'
    #pod 'libksygpulive/libksygpulive',  :path => '../proj/KSYLive_iOS/'
    #pod 'libksygpulive/libksygpulive',  :git => 'git@newgit.op.ksyun.com:sdk/KSYLive_iOS.git', :branch => 'v1.8.6.0'
    pod 'libksygpulive/libksygpulive',  :git => 'http://newgit.op.ksyun.com/sdk/KSYLive_iOS.git', :branch => 'v1.8.6.0'
end

target 'KSYReplayKitDemo' do
	pod 'GPUImage'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    puts "!!!! #{target.name}"
  end
end
