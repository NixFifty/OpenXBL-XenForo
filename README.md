# OpenXBL for XenForo
This is a lite example of how to use OpenXBL with real world aplications. This addon will allow your users to associate an Xbox Live profile with their account and log in using Microsoft credentials. 

NOTICE: This is a very early release and has a limited feature set and could contain bugs. Please feel free to contribute, report issues, or request features. When a user authenticates this way the access token will be encrypted. Use the decrypt function before sending a request to XBL.IO on their behalf. Please use HTTPS. 

Part of the [XBL.IO](https://xbl.io) feature set.

## Installation
1) All the contents in the 'upload' folder should be uploaded to the root directory of your XenForo installation. 

2) Inside 'upload/openxbl.php' modify 'YOUR-XENFORO-URL.COM' with your websites address.

3) Go to your XBL.IO profile and set up the 'Xbox App' in your profile.

4) Inside the XenForo settings for OpenXBL put your Application Key in. 

## Documentation
Reader-friendly Documentation can be found here. [Users Manual](https://xbl.io/docs/xboxapp).

## Support
The following support channels can be used for contact.

- [Twitter](https://twitter.com/OpenXBL)
- [Email](mailto:help@xbl.io)