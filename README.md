# Facebook Share Content
Share photo, video, link , any text from App to Facebook <br />

## Installation
- Get started with Facebook App by following [this](https://youtu.be/2ZdzG_XObDM) tutorial
- Provide your Facebook App ID in [Manifest.xml](blob/master/app/src/main/AndroidManifest.xml) file (Replace {APP_ID} with your Facebook App ID )
- Create a resource file named  `secret_api_key.xml` with following content (Replace {APP_ID} with your Facebook App ID )
```
<resources>

    <string name="secret_facebook_app_id">{APP_ID}</string>
    <string name="secret_facebook_login_protocol_scheme">fb{APP_ID}</string>

</resources>
```

## Usage
- For sharing video from url, follow btnShareLink
- For sharing photo from url, follow btnSharePhoto
- For sharing video from device, follow btnShareVideo


## Prerequisite:
- Facebook app must be installed on the device
- Android version must be >= 4.3

## Acknowledgement
[YouTube - EDMT Dev](https://youtu.be/2ZdzG_XObDM)

## Resources
- [Official Facebook Share SDK Doc](https://developers.facebook.com/docs/sharing/android/)
- [Picasso GitHub](https://github.com/square/picasso)