<h2 align="center">2FA (TOTP / HOTP) </h2> 

Passwords are not being cracked by anyone but the lazy. The recent massive leak of Yahoo accounts only reinforces the fact that a password alone - no matter how long or complex - is no longer enough for strong security. [Two-factor authentication](https://en.wikipedia.org/wiki/Comparison_of_OTP_applications) is what promises to provide that protection, adding an extra layer of security.[^10]

### ❌ Vulnerable (Disadvantages) of 2FA SMS
Receiving OTP codes via SMS or email are one of the weaker ways to secure your accounts with MFA. Obtaining a code by email or SMS takes away from the "something you have" idea, because there are a variety of ways a hacker could take over your phone number or gain access to your email without having physical access to any of your devices at all. If an unauthorized person gained access to your email, they would be able to use that access to both reset your password and receive the authentication code, giving them full access to your account.[^11]

Perhaps not surprisingly, [SMS reigned supreme](https://safenotscammed.com/whats-the-most-popular-form-of-two-factor-authentication-in-2023/), with a whopping 61.5% of the vote. Survey takers said they preferred this method because of how fast and easy it is to use.

SMS can be intercepted either at the ISP level or by replacing or cloning the SIM card
<br>
Physical access to the SIM card will not secure against this kind of protection (the only solution is to set a PIN, which is not very secure)
<br>
Possible SIM card reissuance and phone number spoofing by intruders

### ❗ Possible 2FA TOTP hacking methods
- Gaining ROOT access and extracting a secret from an application
- Unlocking the bootloader also allows you to get any apps data (the only solution is to activate encryption in the app settings, all the apps below allow you to do this)
- Location-based unlocking, facial photo unlocking and the like also allows you to retrieve data
- Using TOTP inside the password manager (which is insecure and an egg in one basket)

### <img width=20px src="https://raw.githubusercontent.com/beemdevelopment/Aegis/master/metadata/en-US/images/icon.png"></img> <a href="https://github.com/beemdevelopment/Aegis">Aegis</a>
✔ Open Source
<br>
✔ Recommends [PrivacyGuides](https://www.privacyguides.org/en/multi-factor-authentication/#aegis-authenticator-android)

### <img width=20px src="https://i.imgur.com/CCcxXJx.png"></img> <a href="https://github.com/twofas">2FAS</a>
✔ Open Source ([recently](https://www.reddit.com/r/Bitwarden/comments/129m0j1/2fas_authentication_app_is_now_open_source/))

<img width=20px src="https://i.imgur.com/R46JaVd.png"></img> https://play.google.com/store/apps/details?id=com.authenticator.authservice2
<br>
<img width=20px src="https://raw.githubusercontent.com/andOTP/andOTP/master/assets/logo.png"></img> https://github.com/andOTP/andOTP
<br>
<img width=20px src="https://i.imgur.com/z4kcqp9.png"></img> https://totp.danhersam.com/
<br>
<img width=20px src="https://github.com/winauth/winauth/blob/master/WinAuth/Resources/WinAuthIcon.png"></img> https://github.com/winauth/winauth
<br>
https://github.com/tobysmith568/totp-online
<br>
https://totp.app
<br>
https://github.com/anrcry/totp-generator

<h3> <img width=20px src="https://site-iota-coral.vercel.app/censor/authy.png"></img> <a href="https://authy.com">Authy - suck!</a> </h3>

❌ Dependent eco-system
<br>
❌ Synchronization and storage on **their** servers is not secure
<br>
❌ Registration by phone number
<br>
❌ Some services [impose](https://gist.github.com/gboudreau/94bb0c11a6209c82418d01a59d958c93) the use of Authy instead of other TOTP applications[^3]
<br>
❌ Desktop applications for TOTP codes are not secure, and ruin the entire principle of two-factor authentication[^4]
<br>
✔ The desktop app closed in August 2024 (the application is [now](https://www.reddit.com/r/privacy/comments/191gu54/authy_2fa_desktop_clients_are_being_discontinued/) [more](https://www.reddit.com/r/Bitwarden/comments/191ikkd/here_is_one_more_reason_to_move_away_from_authy/) [secure](https://www.reddit.com/r/technology/comments/191h5nf/authy_authenticator_apps_for_desktop_are_being/))

[^10]: https://xakep.ru/2017/01/17/two-factor-authentication-hacking/
[^11]: https://www.privacyguides.org/ru/basics/multi-factor-authentication/
[^3]: https://www.reddit.com/r/Twitch/comments/9phayo/why_is_twitch_forcing_us_to_use_authy_as_the_2fa/
[^4]: https://securelist.com/how-to-steal-a-million-of-your-data/91855/
