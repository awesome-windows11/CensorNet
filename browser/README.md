<h1 align="center">🌐 Most private browsers</h1>

A constantly updated guide to the best private browser (not to be confused with anonymous as well as secure, this repository has other goals)

⚠ $\color{orange}{\textsf{Warning!}}$

> As a reminder, anonymity is more affected by other factors than your browser. Tor or VPN will be much more effective than even the most properly configured browser without cookies

The concept of browser fingerprinting, which is often used as an excuse to use a corporate browser in stock configuration, is largely a lost cause and therefore can not practically be taken into consideration when choosing a browser. The argument for fingerprinting is that by using an obscure or lesser-used browser with unusual capabilities (ie has uMatrix, uBlock installed, or is using Netsurf), your fingerprint becomes unique and therefore easy to track. This becomes less of a good thing to base your decision off of when you consider what it would take to make yourself un-fingerprintable (an unachievable misnomer), and how that would make your overall privacy, security and anonymity worse than if you had just used a far more basic browser, devoid of vulnerable features.

https://spyware.neocities.org/articles
<br>
https://web.archive.org/web/20220511020224/https://tilde.club/~acz/shadow_wiki/browsers.xhtml
<br>
https://digdeeper.neocities.org/articles/browsers
<br>
https://gs.statcounter.com

<h2> <img src="https://github.com/awesome-windows11/CensorNet/assets/87380272/8d4f510d-fe61-40bb-b955-e2fbd645318e" width="25px"></img> <a href="https://librewolf.net/">Librewolf</a></h2>

### ✔ $\color{green}{\textsf{Low}}$

### It's open source software!

### Does not have automatic updates (or they can be turned off)

Librewolf is a Firefox fork with the primary goals of privacy, security and user freedom.

Librewolf makes some calls on startup to `f.s.s.m.c.qjz9zk` which looks like an obliterated address, and `shavar.services.mozilla.com which is intended` (however it can be disabled by clearing the URL in browser.safebrowsing.provider.mozilla.updateURL)[^8]

[^8]: https://gitlab.com/librewolf-community/browser/linux/-/issues/271

There is also an attempt to check for updates regarding the pre-installed uBlock Origin extension.

The browser disables accurate geolocation, runs 11 content filters to block trackers and ads, and includes Canvas Protection, which protects against fingerprinting by analyzing how graphics are displayed in the browser.

While it is true that the project themselves do not collect any telemetry, the domains that the browser visits the very first time you open up the browser do log these requests, which - besides from timely updates - is the only problem I have with Librewolf.[^9]

[^9]: https://www.unixsheikh.com/articles/choose-your-browser-carefully.html#librewolf

<h2> <img src="https://github.com/awesome-windows11/CensorNet/assets/87380272/640c38d4-c2ec-49af-9801-88d8b0c5a2f6" width="25px"></img> <a href="https://github.com/ungoogled-software/ungoogled-chromium">Ungoogled Chromium</a></h2>

### ✔ $\color{green}{\textsf{Nothing (?)}}$
Other builds: https://chromium.woolyss.com

### It's open source software!

### Does not have automatic updates

Ungoogled-chromium is Google Chromium, sans integration with Google.

Ungoogled-chromium is a fork of Chrome that has all of Google's spyware removed. It was tested with **MITMproxy and makes no unsolicited requests, and is therefore not spyware**. Ungoogled-chromium is the highest-rated browser based on Google Chrome, and is probably one of the best choices if you can compile it.

Unlike Iridium, Ungoogled-Chromium actually disables all automatic connections and other Google integration. The dev is also a really nice and skilled guy (at least he doesn't have a problem with people reporting stuff - unlike Pale Moon, or worse - Mozilla). However, keep in mind the Chromium codebase is massive, and it's doubtful this single guy can keep up for long (then again, he does lift patches from other similar projects such as Bromite, and has a helpful userbase). He's doing better than the Iridium team, though - with his browser being much more up to date. In the end, Ungoogled-Chromium is still just a bunch of bandages applied to Chromium, and keeps Uncle G in control of the Web. 

<h1 align="center"> 🕵️‍♂️ Tracking / spyware browsers </h1>


<h2> <img src="https://i.ibb.co/jgv4K78/Chrome.png" width="25px"></img> Google Chrome</h2>

### ❌ $\color{red}{\textsf{EXTREMELY HIGH!}}$

Google details the extreme spyware feature it labels "Usage Statistics and Crash Reports". What it does, is it sends very detailed information about your hardware and computer usage, which confirms that it definitely contains the following spyware features:

- A tracker that records mouse input over time
- A tracker that profiles memory usage

But, it can also be extrapolated from the vague language that Chrome could and probably does monitor what other programs you have open. Either way, it is an extreme amount of information being collected, since it can be used to recreate what the user is doing on their desktop at all times. Chrome clarifies that this information is being sent **WHENEVER** a website is being "slow" or whenever Google Chrome crashes.

### Google Chrome contains a keylogger
This was confirmed in multiple places. Basically, whenever you type into the search bar, that information is sent to Google. You can apparently turn it off by opting out of the "suggestion service".

### Google Chrome records your voice
Google Chrome is confirmed to be constantly listening to any open microphones on your computer. This can be found in this statement in a privacy publication. "Voice & audio information may be collected. For example, if your child uses audio activation commands (e.g., "OK, Google" or touching the microphone icon), a recording of the following speech/audio, plus a few seconds before, will be stored to their account…" This feature is opt-in if you are using the "Google Accounts" spyware platform and specifically tell Google to build a profile of your child. It's unverified whether or not Google uploads information it listens too to its servers outside of this feature.

<h2> <img src="https://i.ibb.co/BNtzHDM/Edge.png" width="25px"></img> Microsoft Edge</h2>

### ❌ $\color{red}{\textsf{EXTREMELY HIGH!}}$


### Microsoft Edge scans the pages you visit
Microsoft’s Edge browser appears to be sending URLs you visit to its Bing API website. Reddit users first spotted the privacy issues with Edge last week, noticing that the latest version of Microsoft Edge sends a request to bingapis.com with the full URL of nearly every page you navigate to. Microsoft

https://gist.github.com/niutech/1f1c1518ce0eba7e8d429c812d39493d

### The Edge scans your clipboard[^1]
[^1]: https://www.reddit.com/r/browsers/comments/12o6dje/so_ms_edge_mind_explaining_this_to_me_why_are_you/

I always open msedge (Microsoft Edge) in background to play youtube music videos, or SNS.yet, it monitor/accessing my clipboard. 

### New tab - automatic address connection
The first connection is established to the address "ntp.msn.com", where the currently set search engine (Bing) is transmitted to Microsoft as a parameter. Linked to this call is the opening of the website "www.msn.com", where various resources (JavaScript, stylesheet, images, etc.) are reloaded from sources in order to display the website in the browser[^2]

[^2]: https://www.kuketz-blog.de/microsoft-edge-datensendeverhalten-desktop-version-browser-check-teil4/

In the default configuration, the browser is a serious privacy disaster. Only after adjusting various settings, such as deactivating Defender SmartScreen, changing the search engine and the setting for "new tabs" does it become a bit more privacy-friendly. However, we are far from privacy-friendly, since the transmission of telemetry data can only be reduced during use, but not deactivated.

Microsoft Edge is probably used as the default browser in many companies and institutions. Administrators should take a close look and check the settings and group policies. In my opinion, the browser cannot be used in the default configuration.

And last but not least: Even in "private mode", Microsoft Edge sends EVERY domain or complete URL (incl. parameters) to the cloud - for security reasons. WTF Microsoft!

Let's briefly recall the marketing slogan Microsoft uses to promote the Edge browser:

<h2> <img src="https://github.com/awesome-windows11/CensorNet/assets/87380272/8a9b964c-f244-4bb2-9a0d-14b8d8505923" width="25px"></img> Opera</h2>

### ❌ $\color{red}{\textsf{HIGH}}$
Opera makes about 83 unsolicited requests on its first run:

![image](https://github.com/awesome-windows11/CensorNet/assets/87380272/0816aea8-741d-48f4-9be3-95e5fc7c764f)

By default, it spies on all your browsing. Works closely with advertisers and trackers. It is integrated with Facebook/Meta, one of the biggest privacy violators in the world. Has Google as the default search engine. Closed source.

Anytime you visit a website, Opera will make a request like this to check if it is malicious. So it is literally spying on your whole browsing history

Opera has a list of "partners" — those are the websites that are in the Speed Dial by default.

### Opera is a Chinese company

https://en.wikipedia.org/wiki/Zhou_Yahui

### Opera scans all the sites you visit
Additionally every time you visit a website, when it is finished loading, Opera will make a call to its own servers to an API containing the domain name. Let's say I visit `privacyguides.org` in Opera, when it is finished loading Opera will make a call to: `speeddials.opera.com/api/v1/thumbnails/www.privacyguides.org`

This allows for a complete profiling by Opera of every site you visit with their browser. There is no way to disable this, even through flags.

There aren't many browsers brazen enough to outright collect data directly on every single domain you visit and every keystroke you enter into its address bar. Opera is one of the ones that does. These are the real, tangible issues with this software. People talk a lot about their connections to China, point out their shady dealings in other areas etc. but most people will just brush those off. People need to know, in no uncertain terms, that this browser is sending your entire browsing history to their servers. I'd like to say these issues are just bad design under the hood and not intentionally malicious, but that would be giving them the benefit of the doubt which they've really not earned as a company. Through cynical eyes, it seems they've tried to implement hardcore tracking of what their users type and visit and attempted to hide it behind "innocent" services that they can potentially excuse away as trivial functions if it were brought up.[^7]

https://www.youtube.com/watch?v=NV8akIgfDqQ

[^7]: https://www.reddit.com/r/browsers/comments/14bisgq/opera_gx_video_on_their_shady_practices_cool_and/

<h2> <img src="https://i.ibb.co/0M4JSxx/Vivaldi.png" width="25px"></img> Vivaldi</h2>

### ❌ $\color{red}{\textsf{HIGH}}$
Vivaldi makes about 119 requests on startup, and continues to make unsolicited connections after. Anti-privacy Bing is the default search engine.

**EVEN IF** you disable everything under "Google Services" and "Google Extensions" under "Privacy" in settings, it will still make automatic connections to Google. Also makes connections after first start up to `mirmir.vivaldi.com` and `downloads.vivaldi.com`.

### Vivaldi Assigns you a unique ID
From the Privacy Policy: "When you install Vivaldi browser (“Vivaldi”), each installation profile is assigned a unique user ID that is stored on your computer. Vivaldi will send a message using HTTPS directly to our servers located in Iceland every 24 hours containing this ID, version, cpu architecture, screen resolution and time since last message. We anonymize the IP address of Vivaldi users by removing the last octet of the IP address from your Vivaldi client then we store the resolved approximate location after using a local geoip lookup. The purpose of this collection is to determine the total number of active users and their geographical distribution".

The above cannot be disabled even if you're a programming ninja - because Vivaldi's source code is unavailable! Their New Tab page is filled with various partners' websites by default, including violators such as YouTube and Amazon - though you can fortunately remove those. The default search engine is the anti-privacy Bing. Tracking protection is included but it's off by default. It doesn't seem as if Vivaldi cares about privacy too much - it's also closed source. The only saving grace is the massive amount of features, which is of course significant - but most of those can be replaced with extensions on browsers that support them. There also comes a point where a piece of software is trying to do too much - and Vivaldi might have crossed that bridge already. But at least it's something different compared to all the browsers that are bare-bones.

### Some users claim that Vivaldi is a keylogger
Convenient and functional browser. But spyshelter periodically showed me messages that Vivaldi was trying to register keystrokes (in essence, this is keylogging), and I created a rule forbidding the browser to do this. Once a day he makes an attempt, but spyshelter blocks this action. It is worth saying that periodically Firefox also registers keystrokes, while spyshelter automatically resolves this action. But it's about Vivaldi. Today, after updating the browser to the latest version, spyshelter displayed a message to me that it had not previously displayed. It concerned Vivaldi, who was trying to access BITS interprocess communication, if I write correctly. I didn’t particularly read and allowed this action, because when I blocked the browser began to crash. However, I’m interested in WHAT the browser did, because judging by the spyshelter log, the browser used some kind of utility to copy files from the hard disk or something like that. Recently I found a video where it was said that Vivaldi spies and once a day sends somewhere all the information about user sessions per day, using a unique identifier that is assigned to each user. I don’t know how true this is, and if it’s true, how much detailed information he sends, and whether other browsers do it. Now I’m wondering WHAT is the spyshelter logged for the browser action?[^3]

[^3]: https://malwaretips.com/threads/vivaldi-browser-is-a-spy.98431/

<h2> <img src="https://i.ibb.co/1qCFxLh/brave.png" width="25px"></img> Brave</h2>

### ❌ $\color{red}{\textsf{HIGH}}$

Another rather controversial browser.

Brave is self updating software, uses Google as the default search engine, has built-in telemetry, and even has an opt-out rss-like news feed similar to Firefox Pocket. These shouldn't be the things that come to mind if someone were to imagine a privacy oriented browser.

### Brave has built-in telemetry
While running, Brave will make lots of requests to the domain `p3a.brave.com` as telemetry. They claim they store the collected data for several days. This feature is an opt-out that can be disabled.

### Brave Today
Brave now has new feature similar to Firefox Pocket called Brave Today. If you don't know what Firefox Pocket is, it's basically an rss-like news feed that's shown in every blank tab. This feature Brave has is sadly an opt-out rather than an opt-in and sends lots of requests to Brave's servers. It can't seem to be disabled it in and of itself, but setting the tabs to blank seems to stop the requests.

### SafeBrowsing
Brave uses SafeBrowsing. It's a feature that tries to "protect" the user from potentially unsafe websites and extensions. However, it sends requests to fetch the information required. Brave's SafeBrowsing is powered by google.

### Brave Rewards
Brave has a rewards program. At first glance it looks like the rewards program is an opt-in, but the browser makes requests to these domains regardless if you sign up or not:
- rewards.brave.com
- api.rewards.brave.com
- grant.rewards.brave.com

### The Brave web browser is hijacking links, and inserting affiliate codes[^4]

[^4]: https://davidgerard.co.uk/blockchain/2020/06/06/the-brave-web-browser-is-hijacking-links-and-inserting-affiliate-codes/

Brave has been caught in various schemes such as where when you type a URL to a cryptocurrency link, the browser at one point would redirect you to a different URL that generates them money. Every time they are caught doing something like that and it becomes publicized, they say it was unintentional, and change it. Whether you believe it is unintentional or not is, again, up to you as a user, but the sheer number of times this stuff has happen lead me to believe they are constantly testing to see what users will notice or let them get away with, and pulling back only if it is noticed and there is a backlash. That means, I think, logically, that there is a reasonable possibility that they are testing new schemes today and that people just haven't discovered them yet, and that if they are discovered and disliked by the users, they may be stopped and new ones will be attempted. Actually, that users are potentially being exposed to things that they don't know about, to me is worse than if they upfront said "Here's what we're doing", because the latter would let the user make an informed choice, whereas the former does not.

This browser has made waves thanks to its built-in privacy protections - such as AdBlock, HTTPS everywhere and script blocking - but in the end, they are outclassed by uMatrix. More than that - after checking them out, I can confidently say the Shields are pretty useless - the vast majority of trackers are left alone; in fact, sometimes it seems that a site can have hundreds of them, and yet none of them will be blocked by the Shields. Script blocking option simply blocks JavaScript fully - it's just NoScript revisited. Brave used to be able to install Chrome extensions only from source, but now does it the same as the other Chrome based browsers. Despite those, it not only spies on you (archive) (MozArchive) but is actively working against your privacy by whitelisting Facebook and Twitter trackers. Brave has also been soliciting donations in the name of other people without their consent!

**BROWSER CREATORS WERE CONSTANTLY INVOLVED IN CRYPTO SCANDALS - DON'T USE BRAVE!**

<h2> <img src="https://github.com/awesome-windows11/CensorNet/assets/87380272/ec08b9bf-d18d-4e15-965b-5bf873e173df" width="25px"></img> Waterfox</h2>

### $\color{orange}{\textsf{Medium}}$

Waterfox is a fork of Firefox that claims to be more private and secure than Firefox. However, Waterfox contains telemetry and shares information about you with Mozilla, and has other spyware features.

I never wanted Waterfox to be a part of the hyper-privacy community. It would just feel like standards that would be impossible to uphold, especially for something such as a web browser on the internet. Throughout the years people have always asked about Waterfox and privacy, and if they’ve ever wanted more than it can afford, I’ve always pushed them to use Tor. Waterfox was here for customisations and speed, with a good level of privacy.[^5]

### Waterfox connects to spyware services when it is first run
If you start up Waterfox for the first time, it will make between 31 to 130 requests (most of them being version checks) to several spyware platforms, notably Matomo, and Mozilla online services like its Geolocation service, and several other Mozilla services, as well as Waterfox's own update service. You can look at a list of these requests here:

![image](https://github.com/awesome-windows11/CensorNet/assets/87380272/1ee4e616-391a-46d1-8dc9-4119fbec83ec)

### Waterfox is self updating software
Self updates are a spyware feature since they are usually ways for the developer of a program to put spyware into their software without presenting it in a prominent way where the user can understand what they are giving up when they download the update.

Other known spywares, like Chromium, make use of this method

[^5]: https://www.ghacks.net/2020/02/14/waterfox-web-browser-sold-to-system1/
