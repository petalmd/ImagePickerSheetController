install! 'cocoapods', :deterministic_uuids => false

project 'ImagePickerSheetController/ImagePickerSheetController.xcodeproj/'

platform :ios, '9.0'

use_frameworks!
inhibit_all_warnings!

def all_pods
  #pod 'Nimble', '~> 7.0.0'
end

target 'ImagePickerSheetController' do
  all_pods
  
  pod 'KIF'
end

target 'ImagePickerSheetControllerTests' do
  pod 'KIF', :configurations => ['Debug']
end
