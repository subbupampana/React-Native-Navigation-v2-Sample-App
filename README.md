
<html>
  <h2>Installing on iOS</h2>
  <p>Step 1:Go to ios folder in your root project and open rnnV2Demo.xcodeproj.It will open your project in Xcode</p>
   <img src="./documentation/images_ios/openWorkSpace.png"/>
  <p>Step 2:You project folder something looks like this</p>
  <img src="./documentation/images_ios/foldersinxcode.png"/>
  <p>Step3:In Xcode, in Project Navigator (left pane), right-click on the Libraries > Add files to [project name]</p>
  <img src="./documentation/images_ios/dragdrop.png"/>
  <p>Step4:In Xcode, in Project Navigator (left pane), click on your project (top), then click on your target row (on the "project and targets list", which is on the left column of the right pane) and select the Build Phases tab (right pane). In the Link Binary With Libraries section add libReactNativeNavigation.a</p>
  <img src="./documentation/images_ios/step2.png"/>
  <p>Step 5:In Xcode, you will need to edit this file: AppDelegate.m</p>
    <img src="./documentation/images_ios/finalstep.png"/>
</html>
