# Welcome	
You're here because I've shared access to **Hyperdrive**, my Plex server. Read through this page before starting setup so things go smoothly.

## What is Plex?
Plex is two things:
- **Server software** that organizes and streams a personal media library.
- **Client apps** (web, mobile, smart TV, set-top box) that let you play it.

I run the server software on a computer in my home. That’s **Hyperdrive**, a library of 1,800+ movies and 13,000+ TV episodes that you connect to through Plex’s apps. 

> - Plex = the company and its apps
> - Hyperdrive = my Plex server (the actual library you're accessing)

![home.png](/images/home.png)

## Is it safe?
Yes. Plex is designed for personal use, and it only does one thing: stream media. The apps you install come directly from Plex, the company, and work the same way as Netflix or Disney+: they request video, and the server streams it back.

When you stream from Hyperdrive, you’re not opening your device up to me or to strangers. You’re just telling the Plex app to stream video from my server instead of from a corporate data center.

On my end, I take care of running the server and handling the risks. On your end, it’s no different than using any other streaming app. 

## Why use this instead of other streaming services?
Streaming services are convenient, but each one only offers part of the picture. Some carry a handful of seasons, others rotate titles in and out, and many keep splitting content across new subscription tiers.

With Hyperdrive, everything is in one place. There’s no guessing which service has what, or whether a movie quietly disappeared last week. The library stays stable, searchable, and ready when you are.

And unlike commercial platforms, Hyperdrive doesn’t push recommendations or hide titles behind algorithms. The experience is consistent: open Plex, find what you want, press play.

## I'm in
If you’re ready to join, just share your email address with me. I’ll send you an invite to Hyperdrive, and then you can follow the steps in the next section to get started.

# Getting Started
> These instructions assume you’re on a computer. The steps may look different on mobile.

1. Accept the invite

    Check your email for a message from noreply@plex.tv with the subject line “You’ve been invited to share some media in Plex.” It looks like this:

    ![share_email.png](/images/share_email.png)

    Click `I accept the invitation`.

2. Sign in or create an account
    
    You’ll be taken to the Plex sign-in page. 
    - If you already have a Plex account, just sign in.
	- If you’re new, you can use Google or Apple single sign-on, or click `sign up with email`.

    > **Important:** Use the same email address I invited. If you choose `Continue with Apple` and hide your email, let me know the randomized iCloud relay address so I can invite the correct email address.

    ![signup.png](/images/signup.png)

3. Confirm library access

    After signing in, you’ll land on the **Manage Library Access** page. You should see two libraries shared with you: Movies and TV Shows. 

    ![library_access.png](/images/library_access.png)

4. Adjust Plex settings

    Plex offers its own ad-supported content, but to avoid confusion, I recommend disabling all of it.
	- In the sidebar, click `Online Media Sources` and disable every option.

    ![online_disabled.png](/images/online_disabled.png)

    The following changes only apply to Plex Web. Please make the same adjustments on every platform on which you plan to use Plex. 

    - Click `Quality` in the side bar, here are my recommended settings: 

    ![recommended_settings.png](/images/settings.png)
   
    - Click `Quality` in the sidebar. Set video quality to `Maximum`. This prevents unnecessary transcoding on my end and gives you full-quality playback.
    > If you have limited bandwidth or frequent buffering, you can enable Automatically adjust quality (Beta).
    - Click `Player` in the sidebar, `Show Advanced`, and disable `Normalize Multi-channel Audio`.
    - Finally, click  `General` under "Plex Web" on the left-hand sidebar. Feel free to enable `Play Theme Music`, I think it's kinda fun.

5. Finish Setup

    Now, click on the home button in the top left corner, and you'll see the **Plex Web Setup** page, with a list of pinned sources. If you successfully disabled the online media sources, you shouldn't see many options. If you see `Live TV`, `Movies & Shows`, or `Discover`, make sure they're unchecked.

    ![unpin.png](/images/unpin_setup.png)

    Finally, click `Finish Setup`. You should be greeted by the Home page: 

    ![finally_home.png](/images/finally_home.png)

# Next Steps
You now have a Plex account connected to Hyperdrive with the right settings in place. You’re ready to start streaming. 

## Download Apps

Plex has apps for just about every device you might want to watch on:
- **Desktop:** [Mac](https://www.plex.tv/media-server-downloads/?cat=plex+desktop&plat=macos#plex-app) · [Windows](https://www.plex.tv/media-server-downloads/?cat=plex+desktop&plat=win#plex-app)
- **Mobile:** [iOS](https://itunes.apple.com/us/app/plex/id383457673?mt=8) · [Android](https://play.google.com/store/apps/details?id=com.plexapp.android&hl=en)
- **Set-top boxes and smart TVs:** Apple TV, Roku, Fire TV, Nvidia Shield, and most modern smart TVs.

## Remote Streaming
Plex used to require a one-time $5 unlock to stream remotely on mobile devices. [As of April 2025](https://www.plex.tv/blog/important-2025-plex-updates), Plex requires a subscription for *any* streaming outside the server's local network. Normally, that would mean either a Plex Pass or a Remote Watch Pass.

Because I already have a Plex Pass, you don’t need to worry about subscriptions — **all Hyperdrive users can stream remotely at no cost**. You should never be asked to pay Plex to watch from my server.

## Request Something New
If there's something you want to watch that isn't yet on Hyperdrive, you can request it yourself. Let's get set up with Jellyseerr, my automated request management platform:

1. Visit [jellyseerr.cartersanderson.com](https://jellyseerr.cartersanderson.com) in your browser.
2. Sign in with your Plex account.
3. Search for the movie or TV show you want and select `Request`.
4. That's it! Media is usually available shortly after submission.

Unfortunately, Jellyseerr does not offer a native application. Luckily, it _is_ a PWA (**P**rogressive **W**eb **A**pp), which means it will behave just like an app if you add it to your Home Screen. From [jellyseerr.cartersanderson.com](https://jellyseerr.cartersanderson.com):

1. Select the share icon (a square with an arrow coming out of it) and tap `Add to Home Screen`.
2. Open the Jellyseerr app icon from your Home Screen. 
3. Sign into your Plex account.
4. **(Optional)** Enable push notifications to get an alert as soon as your requested media is available.
> Go to `Settings` > `Notifications` > `Web Push`, and make sure all the options are enabled. Then tap `Enable web push` and then `Save Changes`. 

![jellyseerr_homescreen.png](/images/jellyseerr_homescreen.png)

From then on, anytime you want something new, just open Jellyseerr, search, and tap `Request`. That’s it.

## Notice an issue with content? 
If you notice a problem while watching something (video, audio, or subtitles), let me know so I can fix it. You have two easy options:

1. **In  Plex:**  On the episode or movie page, open the three-dot menu and select `Report Issue...`

    ![issue_plex_1](/images/issue_plex_1.png)

2. **In Jellyseerr:** Open [Jellyseerr](https://jellyseerr.cartersanderson.com) and click on the yellow `Report an Issue` button on the right side.

    ![issue_overseerr_1.png](/images/issue_overseerr_1.png)

    > The more detail you include, the faster I can fix it. Note timestamps, whether the problem is with video, audio, subtitles, or something else, and any troubleshooting you’ve already tried.

## Having a more serious problem? 
I’ve worked hard to make Hyperdrive as smooth and automated as possible, but problems can still pop up. If you run into an issue that completely prevents you from streaming (such as "Hyperdrive is currently unavailable" or a 404 error on Jellyseerr), check the [Hyperdrive Status dashboard](https://status.cartersanderson.com) first. If the dashboard reports an outage, I’m likely already aware and working on it. If everything looks normal on the dashboard but you still can’t stream, feel free to text me with a quick note about what you’re seeing.

![status_dashoard.png](/images/status_dashboard.png)

<!-- ![unavailable.png](/images/unavailable.png) -->

## Other fun stuff
I take pride in keeping Hyperdrive polished and well-organized. One of the best features is the `Collections` tab inside the `Movies` library. Here you’ll find movies grouped not just by franchise (*Shrek*, *The Godfather*), but also by studios, directors, Oscar winners, IMDb lists, and more. If you’re not sure what to watch, this is a great place to start browsing. 

![collections.png](images/collections.png)

Plex also has a shuffle button! You can shuffle TV shows, collections, or if you're feeling brave, you can even shuffle the entire library. 

## FAQs
1. What’s Hyperdrive? 
    > Hyperdrive is the name of my Mac mini that runs Plex Server. You’ll see it from time to time. All my devices are named after Star Wars references.
2. Why isn’t a requested movie available yet? 
    > Media can only be added once it's available outside theaters (e.g. on streaming, VOD, or Blu-ray/DVD). Very obscure or older titles may not be sourceable. 
3. Why no 4K or Remux? 
    > 4K and Remux files have huge bitrates that can create more problems than benefits. They strain both my server and your devices, so I stick with smaller, more reliable formats. They also take up way more space, so lower resolution means more available media. 
4. What resolution is the content?
    > Movies: highest available quality, up to 1080p. TV shows: usually 720p to conserve space. 
5. Why are there more than 250 movies in the IMDb Top 250 Collection? 
    > I have multiple editions of the _Star Wars_ and _The Lord of the Rings_ trilogies, and each edition is counted as a separate movie within the collection.    
6. What hardware is your Hyperdrive running on? 
    > Hyperdrive is an M4 Mac mini with 16 GB Unified Memory, and media is stored on 20 TB hard drives in an OWC Mercury Elite Pro Quad enclosure.
