install! 'cocoapods', :deterministic_uuids => false

project 'ImagePickerSheetController/ImagePickerSheetController.xcodeproj/'

platform :ios, '9.0'

use_frameworks!
inhibit_all_warnings!

target 'ImagePickerSheetController' do
  pod 'KIF'
end

target 'ImagePickerSheetControllerTests' do
  pod 'KIF', :configurations => ['Debug']
  pod 'Nimble', '~> 7.0.0'
end
