# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'
flutter_application_path = './my_flutter/'
  load File.join(flutter_application_path, '.ios', 'Flutter', 'podhelper.rb')
target 'TestFlutterBoot' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  # Pods for TestFlutterBoot
  install_all_flutter_pods(flutter_application_path)
  target 'TestFlutterBootTests' do
    inherit! :search_paths
    # Pods for testing
    install_all_flutter_pods(flutter_application_path)
  end

  target 'TestFlutterBootUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
