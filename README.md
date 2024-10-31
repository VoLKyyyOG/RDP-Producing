# Introduction
Hey all, this tutorial is designed to get you producing remotely from a laptop to a home desktop setup without the need of tedious cloud storage services, duplicate Digital Audio Workstations (DAWs), projects, and so on...
I thought this would have been a common thing but it turns out it's probably a programming oriented mindset, so I'm here to Knowledge Share this to everyone who's interested!

If you found this helpful, check out my stuff [here](https://soundcloud.com/akira_takihara) :P - I'm known for Australian-style Frenchcore and my signature kicks!

...oh, and this doesn't matter if you're on MacOS, Windows, or even Linux. This is cross-platform compatible! 

#### Disclaimer
Just an FYI that I have done research on what suited my security and privacy needs, but this may not meet yours. I hold no guarantees on how you use this method and what happens, but it works for me without any issues.

# Remote Desktop Setup
1. Find a RDP (Remote Desktop Protocol) of your choice. I personally decided on [Rust Desk](https://rustdesk.com/) because it is *open-source* and *free*. This means that anyone in the public is able to verify and check the source code to ensure that the company or software you are downloading is not malicious.
2. Download and install it on *both your devices* (1 for your laptop, 1 for your desktop).
3. **On your Desktop:** Open up the settings, and for the love of god enable 2 Factor Authentication (2FA). I also recommend you set up a *permanent* password (which you can change or rotate every time you come back from your holidays producing remotely). This will allow you to connect remotely with the same password and the 2FA code from your device to connect, rather than physically going to your desktop and looking at the newly generated password (which voids the purpose of this setup). Lastly, there should be a numeric code stating the ID of your desktop which you will require to connect to - copy that down.
4. **On your Laptop:** Open up the settings and enable 2FA. That's it for this part.
5. Now, all steps below **will be from your laptop**.
6. Enter the numerical code you copied down from Step 3, enter the password you created, as well as your 2FA code.
7. An initial connection should be made and you should be able to access your desktop *from* your laptop, you are now done for this part of the tutorial!

Now, you have made a connection but I would recommend you play around with your settings:
- Make sure your desktop isn't playing from monitor speakers (try the headphones driver) or you'll face music blasting while you're overseas (and perhaps annoyed neighbours).
- The screen resolution scaling can be a bit cooked sometimes, so I recommend you set it to the native aspect ratio (usually 1080p or 1440p). Your laptop screen is probably smaller than your desktop but it is what it is.

... and yes, the audio you get from this works but sucks ass and is compressed. We do have a solution for this.

# Low-Latency High-Fidelty Audio Setup
This requires a plugin to be installed *on your desktop* and *DAW of choice*. If you aren't using Ableton tbh, I would recommend you switch because programmatically, it is far better than the competitors.

1. Head over to [Audio Movers](https://audiomovers.com/) and download the `Listen To` Plugin. You can either try it for a trial, purchase it, or find a cracked version.
2. Install the plugin on your host DAW and follow the instructions to set it up.
3. Try the link out from another device and make sure the audio is coming through and working. Once completed, that's it for this part of the tutorial!

# Bringing it Together!
So, how can we bring this all together for a remote producing setup? Let's go through a workflow *assuming* you're gonna be on a holiday with internet access.

For my case, I have a WindowsOS desktop setup and MacOS laptop, so this does work.

1. Before you leave your home, leave your desktop running with Rust Desk (or your RDP of choice). There are ways to power the desktop remotely but if you want to do that, you'll need to be a bit more technically experienced (and if you are then you'll be able to figure it out anyways).
3. Let's say you are now in a different country or state, and you open your laptop to produce (hopefully you brought your headphones).
4. From the setup, the desktop should be saved to your Rust Desk on your laptop. Enter your password as well as the 2FA code.
5. Now, you have access to your desktop remotely! You can then open your project and chuck the `Listen To` VST onto the *end* of your master chain.
6. Create the hyperlink from `Listen To` and send the URL to your laptop.
7. From your laptop, mute the remote desktop session (so there's no audio) and use the audio from the `Listen To` URL.
8. Congratulations! Assuming a good internet connection, you now have a fully remote producing setup with low-latency and high-fidelity audio, no duplicate DAWs, shitty cloud storage (and waiting for stuff to upload), god forbid the duplicate samples and plugins you'll need.

Once again, if you found this useful chuck us a follow on [SoundCloud](https://soundcloud.com/akira_takihara) and share this knowledge around. I'm all for sharing this and making sure everyone can achieve what they want to - fuck the gatekeeping clowns 😹 





