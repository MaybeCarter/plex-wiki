# Welcome	
If you're reading this, it's because I've shared my Plex library with you. You might have some questions. *I recommend reading through this all first before going through the setup.*

## What is Plex?
Plex is a media server that I run on my own computer. Think of it as a streaming service like Netflix or Hulu, but all the content is stored on a computer in my living room. You have access to over 1,500 movies and over 10,000 TV episodes.

![home.png](/images/home.png)

## Is it safe?
Yes. Plex only serves media (in the case of my server, only video). There's nothing that could harm you. My family, a few select friends, and I have been using Plex for more than a year now without any issues. I'm assuming all of the risk. 

## Why use this instead of other streaming services?
My favorite thing about Plex is that everything I'm watching is in one place. It cannot be overstated how convenient it is to never have to look up what streaming service, if any, a particular movie or show is on. You also never have to worry about content leaving Plex due to complicated licensing battles like you do with Big Streaming. And while you get to have access to my Plex server, it's really a personal hobby project that started because I wanted more control than the streaming services I was using. 

## I'm in
Sweet. If I don't have it already, send me your email address so I can invite you.

# Getting Started
> This assumes that you're on a computer. Steps may be different on mobile.

Check your email. You should have received an email from noreply@plex.tv with the subject "You've been invited to share some media in Plex."
*Don't worry, you're not sharing media with me, and the only way that could happen is if you download and setup a server. You'd know.*

It will look like this: 

![share_email.png](/images/share_email.png)

Click `I accept the invitation`.

You'll be greeted with the "Account Sign in" page. If you already have a Plex account, just sign in. Otherwise, select one of the "Continue with..." options to use a single sign on, or  click the dark grey `sign up with email` text under the `Sign In` button. 

> Make sure the method you sign in with uses the same email address that I sent the invite to. If you used `Continue with Apple` and chose to hide your email, I need the obfuscated email address (it'll be something like seniors_reprint_00@icloud.com or spender_pet.0o@icloud.com), not your actual iCloud email address. 

![signup.png](/images/signup.png)

Once you've signed in, you'll be on the "Manage Library Access" page. You should see that you have access to two libraries shared by me (Movies and TV Shows). 

![library_access.png](/images/library_access.png)

Before we go to the Home page, let's make some quick settings adjustments:
> These changes will only apply to Plex Web. Please make the same adjustments on every platform on which you plan to use Plex. 

- Click `Quality` in the side bar, here are my recommended settings: 

    ![recommended_settings.png](/images/settings.png)
   
    > At the very least, set video quality to `Maximum`. This is for my benefit and yours; Hyperdrive won't spend unnecessary resources transcoding media to a lower resolution or bitrate, and you receive the full-quality media. However, you may find it useful to enable `Automatically adjust quality (Beta)` if you have limited bandwidth and face issues streaming.
- Next, click `Player` in the sidebar, `Show Advanced`, and disable `Normalize Multi-channel Audio`.
- Finally, click  `General` under "Plex Web" on the left-hand sidebar. Feel free to enable `Play Theme Music`, I think it's neat.

Now, click on the home button in the top left corner, and you'll see the "Plex Web Setup" page, with a list of pinned sources. Uncheck everything except `Movies` and `TV Shows`. It's up to you if you want to keep `Watchlist` pinned or not. The other items are not shared by me, and will only make your Plex experience more confusing. 

![unpin.png](/images/unpin_setup.png)

Once you've unchecked `Playlists`, `Live TV`, `Movies & Shows`, `Discover`, and `Music`, (and `Watchlist`, if you want) click `Finish Setup`. 

You should be greeted by the Home page: 

![finally_home.png](/images/finally_home.png)

# Next Steps
Great! You made a Plex account and got all set up for an optimal streaming experience. 

## Download Apps
Plex has apps for pretty much every device you'd ever want to stream media on. If you're on desktop, download the  app [here for Mac](https://www.plex.tv/media-server-downloads/?cat=plex+desktop&plat=macos#plex-app) or [here for Windows](https://www.plex.tv/media-server-downloads/?cat=plex+desktop&plat=win#plex-app). If you're on mobile, tap [here for iOS](https://itunes.apple.com/us/app/plex/id383457673?mt=8) or [here for Android](https://play.google.com/store/apps/details?id=com.plexapp.android&hl=en). Plex used to require a one-time in-app purchase of $5 to stream on mobile. However, as of April 2025, that option has been removed in favor of a new Remote Watch Pass subscription. Not to worry, since I own a Plex Pass, it is free for all Hyperdrive users to stream remotely on any device. You should **never** be asked to pay to stream on Plex.

Plex is also available on all major set-top boxes and smart TVs. 
> If you have both a smart TV and a set-top box (like an Apple TV, Roku, or Nvidia Shield), I _beg_ you to use the Plex app on the set-top box instead of the smart TV app. Smart TV apps are extremely resource-constrained and provide a significantly inferior experience to their set-top box counterparts.

_Settings wiki page coming soon_

## Can't Find What You Want? 
If there's something you want to watch that isn't yet on Hyperdrive, you can request it yourself. Let's get set up with Overseerr, my automated request management platform:

1. Go to [overseerr.cartersanderson.com](https://overseerr.cartersanderson.com). 
2. Sign in with your Plex account.
3. Search for the movie or TV show you want and select `Request`.
4. That's it! Media is usually available within minutes of request submission.

Unfortunately, Overseerr does not offer a native application. Luckily, it _is_ a PWA (**P**rogressive **W**eb **A**pp), which means it will behave just like an app if you add it to your Home Screen. From [overseerr.cartersanderson.com](https://overseerr.cartersanderson.com):

1. Select the share icon (a square with an arrow coming out of it) and tap `Add to Home Screen`.
2. Open the Overseerr app icon from your Home Screen. 
3. Sign into your Plex account.
4. **(Optional)** Enable push notifications to receive an alert when requested media is available.
    > Go to `Settings` > `Notifications` > `Web Push`, and making sure all the options are enabled. Then tap `Enable web push` and then `Save Changes`. 

![overseerr_homescreen.png](/images/overseerr_homescreen.png)

Now, anytime you want to watch anything that isn't yet on my server, just open up Overseerr, search for the content you want and select `Request`! It's that easy.

## Notice an issue with content? 
If you're watching something and you notice an issue with the content, let me know! (Not directly - it's not you, but I'll probably forget about it.) You have two options:

1. **Within  Plex (Preferred):**  On the page for the episode or movie that has an issue, click the three dot button and select `Report Issue...` from the dropdown.

    ![issue_plex_1](/images/issue_plex_1.png)

2. **Within Overseer:** Find the item on [Overseerr](https://overseerr.cartersanderson.com) and click on the yellow `Report an Issue` button on the right side.

    ![issue_overseerr_1.png](/images/issue_overseerr_1.png)

    >  The more detail you can provide in your Issue Report, the better! Include timestamps, if the issue is with video, audio, subtitles, or something else, and any troubleshooting you've already completed.

## Having a more serious problem? 
I've put a lot of effort into making the experience as polished and automated as possible. However, problems may pop up from time to time. If you run into an issue that completely prevents you from streaming (such as "Hyperdrive is currently unavailable" or a 404 error on Overseerr), shoot me a text and I'll do my best to fix the issue. 

![unavailable.png](/images/unavailable.png)

## Other fun stuff
I take pride in hosting an aesthetically pleasing and well-organized server. One of my favorite parts is the `Collections` tab within the `Movies` library. Not only are movies organized by franchise (like *Shrek* or *The Godfather*), there are also collections for studios, directors, Oscars, and IMDb lists, and more. If you don't know what you want to watch, the Collections tab is a great place to start. 

![collections.png](images/collections.png)

Plex also has a shuffle button! You can shuffle TV shows, collections, or if you're feeling brave, you can even shuffle the entire library. 

## FAQs
- Thanks for letting me access your Plex server! Can I pay you for your generosity? 
    > **No.** Please don't. Selling access to a Plex server is strictly against Plex's terms of service and could get my whole server shut down. Don't be the person to ruin it for everyone. If you want to support Plex, you can [purchase Plex Pass](https://www.plex.tv/plex-pass/), which will get you features like Skip Intro/Credits and extra content like cast interviews and deleted scenes. 
- I keep seeing the word "Hyperdrive." What's that? 
    > I love _Star Wars_, and I love a naming convention. All of my devices  are named after people, places, and things from the _Star Wars_ universe. Hyperdrive is the name of the Mac mini that Plex is running on, so you might see that name from time to time.
- I requested a movie a while ago, but it's still not available on Plex. Why not? 
    > For me to host it on Plex, a movie has to be available outside of theaters. If it's not available on streaming, video on-demand, or DVD/Bluray, it won't be available on Plex. Additionally, though I'll always try my best, I might not be able to source obscure or especially old media. 
- Why don't you have any 4K or Remux content on your server? 
    > Even if I had infinite storage space (which I don't), 4K and Remux files are such high bitrate that they're more hassle than they are worth, for both my server and your client. 
- What resolution is the content on your server?
    > For movies, the files are the highest quality available, up to 1080p. Since TV shows are so much longer than movies, I keep most of them at 720p to conserve storage space. 
- Why are there more than 250 movies in the IMDb Top 250 Collection? 
    > I have multiple editions of the _Star Wars_ and _The Lord of the Rings_ trilogies, and each edition is counted as a separate movie within the collection.    
- What hardware is your Hyperdrive running on? 
    > ~~My Plex server is running on a late 2014 Mac mini with a 2.6 GHz Dual-Core Intel Core i5 and 8 GB 1600 MHz DDR3 memory.~~
    
    > Since January 2025, my Plex Server is running on an M4 Mac mini with 16GB Unified Memory. The media lives on a series of 20TB hard drives housed in an OWC Mercury Elite Pro Quad enclosure.
