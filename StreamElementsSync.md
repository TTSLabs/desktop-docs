# Instructions for TTSLabs 2.0.18 StreamElements integration:

When StreamElements integration is enabled, three things happen:

1. Media controls and some settings can be controlled directly from Streamlabs (by streamer **and mods**).
2. Those controls and settings are disabled in the app.
3. TTS is synced with on-screen alerts. TTS won't play until an alert appears on screen, and it will automatically apply all the donation filters that StreamElements normally would.

---

# Features

You can play/pause, mute/unmute, and skip alert:

![image](https://user-images.githubusercontent.com/86311854/125003449-3efb4b00-e025-11eb-958c-47d694fb0889.png)

You can replay an alert:

![image](https://user-images.githubusercontent.com/86311854/125003550-71a54380-e025-11eb-87a5-3dfeb2a0ced0.png)

You can reload the app:

![image](https://user-images.githubusercontent.com/86311854/125003601-8eda1200-e025-11eb-98e1-d556cd0caa24.png)

You can set profanity settings:

![image](https://user-images.githubusercontent.com/86311854/125004160-ecbb2980-e026-11eb-9ae0-46bba9c8c62b.png)

# Widget features

You can globally enable/disable TTS and change volume:

![image](https://user-images.githubusercontent.com/86311854/125003998-7fa79400-e026-11eb-8a3c-133fe84a8784.png)

You can change those settings for separate alert types:

![image](https://user-images.githubusercontent.com/86311854/125003985-78808600-e026-11eb-8272-613b3d931add.png)

You can set custom regex filters for advanced donation filtering:

![image](https://user-images.githubusercontent.com/86311854/125004025-9352fa80-e026-11eb-80f0-b731fa14ab3b.png)

---

# Widget installation

Go to [your StreamElements overlays](https://github.com/TTSLabs/desktop-docs/blob/main/StreamElements_Widget_Fields.json).

Click "Create blank overlay":

![image](https://user-images.githubusercontent.com/86311854/125004540-bdf18300-e027-11eb-9f13-c7f1a21eebc6.png)

Give it a name:

![image](https://user-images.githubusercontent.com/86311854/125004607-e4172300-e027-11eb-9b1d-1728892d1cc1.png)

Click "Add Widget" or "+":

![image](https://user-images.githubusercontent.com/86311854/125004641-f729f300-e027-11eb-9ec8-5d928fa6cc19.png)

Click "Static / Custom" > "Custom Widget":

![image](https://user-images.githubusercontent.com/86311854/125004681-0e68e080-e028-11eb-856b-a9041ee9c080.png)

Expand "Settings" on the left and click "Open Editor":

![image](https://user-images.githubusercontent.com/86311854/125004724-250f3780-e028-11eb-90dc-852656847855.png)

Click "Fields", copy-paste [this text into it](https://github.com/TTSLabs/desktop-docs/blob/main/StreamElements_Widget_Fields.json), then hit "Done".

![image](https://user-images.githubusercontent.com/86311854/125004862-6d2e5a00-e028-11eb-8a56-bbc63a522f6c.png)

Hit "Save" in the top-right.

![image](https://user-images.githubusercontent.com/86311854/125004908-87683800-e028-11eb-8aa8-6d3a8dee53b0.png)

Now if the app has "StreamElements sync" enabled, all settings will automatically get synced from the widget.

NOTE: Make sure you only have one copy of this overlay/widget installed, as any duplicate copies will get ignored.
