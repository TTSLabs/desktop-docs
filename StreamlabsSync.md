# Instructions for TTSLabs 2.0.18 Streamlabs integration:

When Streamlabs integration is enabled, three things happen:
1. Streamlabs media controls (like play/pause) work.
2. Some settings are read directly from Streamlabs.
3. TTS is synced with on-screen alerts. TTS won't play until an alert appears on screen, and it will automatically apply all the donation filters that Streamlabs normally would. 

---

# Features

You can play/pause, mute/unmute, and skip alert:

![image](https://user-images.githubusercontent.com/86311854/122953370-aa1dff80-d34c-11eb-8670-e4ad84fd52d7.png)

You can replay an alert:

![image](https://user-images.githubusercontent.com/86311854/122953468-be61fc80-d34c-11eb-8350-829d4a76dbfe.png)

You can set TTS volume:

![image](https://user-images.githubusercontent.com/86311854/122954040-1993ef00-d34d-11eb-80df-89e359e765c1.png)

You can reload the app:

![image](https://user-images.githubusercontent.com/86311854/122954081-21ec2a00-d34d-11eb-9dd1-7ea98735f0db.png)

You can enable/disable **donation** TTS. (Note: You might want to set this volume to 0 so the Streamlabs voice doesn't interrupt the TTSLabs voice.):

![image](https://user-images.githubusercontent.com/86311854/122955378-0fbebb80-d34e-11eb-8491-4bbb6be410ac.png)

Same with **cheer** TTS:

![image](https://user-images.githubusercontent.com/86311854/122955714-54e2ed80-d34e-11eb-8543-e104fa4e2b45.png)

---

# Quirks

Due to limitations of the Streamlabs API, we cannot read these settings from Streamlabs directly. We can only catch them at the moment they are updated. If you change a setting while the app is closed, then you re-open the app, the setting won't be changed.

To make sure the settings all match, you can do the following when the app is open:
- Toggle mute/unmute once.
- Toggle play/pause once.
- Change any Streamlabs alert setting and press save.

This will be fixed in a future release. Streamlabs is currently working with us on a solution.
