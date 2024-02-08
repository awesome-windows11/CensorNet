<h2 align="center">2FA (TOTP / HOTP) </h2> 

Passwords are not being cracked by anyone but the lazy. The recent massive leak of Yahoo accounts only reinforces the fact that a password alone - no matter how long or complex - is no longer enough for strong security. Two-factor authentication is what promises to provide that protection, adding an extra layer of security.[^10]

### ❌ Vulnerable (Disadvantages) of 2FA SMS
Receiving OTP codes via SMS or email are one of the weaker ways to secure your accounts with MFA. Obtaining a code by email or SMS takes away from the "something you have" idea, because there are a variety of ways a hacker could take over your phone number or gain access to your email without having physical access to any of your devices at all. If an unauthorized person gained access to your email, they would be able to use that access to both reset your password and receive the authentication code, giving them full access to your account.[^11]

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

<h3> <img width=20px src="https://raw.githubusercontent.com/beemdevelopment/Aegis/master/metadata/en-US/images/icon.png"></img> <a href="https://github.com/beemdevelopment/Aegis">Aegis</a> </h3>
✔ Open Source

<h3> <img width=20px src="https://i.imgur.com/CCcxXJx.png"></img> <a href="https://github.com/twofas">2FAS</a> </h3>
✔ Open Source ([recently](https://www.reddit.com/r/Bitwarden/comments/129m0j1/2fas_authentication_app_is_now_open_source/)

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

❌ Зависимая эко-система
<br>
❌ Синхронизация и хранение на их серверах не является безопасным
<br>
❌ Регистрация по номеру телефона
<br>
❌ Некоторые сервисы навязывают использовать Authy, вместо других TOTP приложений[^3]
<br>
❌ Настольные приложения для TOTP кодов не являются безопасными, и рушат весь принцип двухфакторной аутентификации[^4]

[^10]: https://xakep.ru/2017/01/17/two-factor-authentication-hacking/
[^11]: https://www.privacyguides.org/ru/basics/multi-factor-authentication/
[^3]: https://www.reddit.com/r/Twitch/comments/9phayo/why_is_twitch_forcing_us_to_use_authy_as_the_2fa/
[^4]: https://securelist.com/how-to-steal-a-million-of-your-data/91855/
