com.apps-pi.securedeviceidentifier
-----------------------------

### Install to project:
cordova plugin add https://github.com/cemerson/cordova-securedeviceidentifier.git

### Remove from project:
cordova plugin rm org.apache.cordova.plugins.SecureDeviceIdentifier

### Changes

#### 20160615
- Fix for deprecated string that prevented latest Xcode from building

#### 2015000?
- Removed All platforms except IOS for now :(
- Updated plugin files to work in CDV 3 CLI
- Updated SecureDeviceIdentifier.m to eliminate Background Thread warning in Xcode (reference: http://goo.gl/JokRZw)
