<h1 align="center">🌐 Most private browsers</h1>

A constantly updated guide to the best private browser (not to be confused with anonymous as well as secure, this repository has other goals)

As a reminder, anonymity is more affected by other factors than your browser. Tor or VPN will be much more effective than even the most properly configured browser without cookies 

The concept of browser fingerprinting, which is often used as an excuse to use a corporate browser in stock configuration, is largely a lost cause and therefore can not practically be taken into consideration when choosing a browser. The argument for fingerprinting is that by using an obscure or lesser-used browser with unusual capabilities (ie has uMatrix, uBlock installed, or is using Netsurf), your fingerprint becomes unique and therefore easy to track. This becomes less of a good thing to base your decision off of when you consider what it would take to make yourself un-fingerprintable (an unachievable misnomer), and how that would make your overall privacy, security and anonymity worse than if you had just used a far more basic browser, devoid of vulnerable features.

https://spyware.neocities.org/articles
<br>
https://web.archive.org/web/20220511020224/https://tilde.club/~acz/shadow_wiki/browsers.xhtml
<br>
https://digdeeper.neocities.org/articles/browsers
<br>
https://gs.statcounter.com

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