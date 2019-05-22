# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'iOSDemo' do
  flutter_application_path = '../my_flutter/'
  eval(File.read(File.join(flutter_application_path, '.ios', 'Flutter', 'podhelper.rb')), binding)

  # Pods for iOSDemo

  target 'iOSDemoTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'iOSDemoUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
