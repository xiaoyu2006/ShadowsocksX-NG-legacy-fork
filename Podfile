# Uncomment this line to define a global platform for your project
# platform :ios, '9.0'
platform :macos, '10.12'

target 'ShadowsocksX-NG' do
  # Comment this line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for ShadowsocksX-NG
  pod 'Alamofire', '~> 4.7.2'
  pod "GCDWebServer", "~> 3.0"
  pod 'MASShortcut', '~> 2'
  
  # https://github.com/ReactiveX/RxSwift/blob/master/Documentation/GettingStarted.md
  pod 'RxSwift',    '~> 5'
  pod 'RxCocoa',    '~> 5'

  target 'ShadowsocksX-NGTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

target 'proxy_conf_helper' do
  pod 'BRLOptionParser', '~> 0.3.1'
end
