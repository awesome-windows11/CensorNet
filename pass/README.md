Everything you need to know about passwords and protecting your personal account(s)

<h2 align="center">🛡 Pass</h2>

Use [mnemonics](https://safe.roskomsvoboda.org/passwords/) or song lines to create passwords (the security of this method is questionable!)
<br>
Use [password card](https://habr.com/ru/articles/534494/)/[matrix](https://rjfelix.github.io/password-matrix/) or hash files (security in question!)
<br>
Use [wijener cipher](https://findhow.org/5076-shifr-vizhenera-onlajn.html) for passwords
<br>
Use constant numbers or HEX color codes to create PIN codes (so you don't have to store them explicitly anywhere)
<br>
Use mathematical expressions with constants to create PIN codes
<br>
Important passwords are still best kept exclusively [in your head](https://book.cyberyozh.com/ru/sozdanie-nadezhnogo-parolya/) so that they are not written down anywhere (high importance passwords).
<br>
[Use](https://book.cyberyozh.com/ru/sekretyi-nadezhnogo-parolya/) sign [zero width](https://symbl.cc/ru/200B/)
<br>
Use passwords [generator](https://bitwarden.com/password-generator/)
  
### <img width=20px src="https://site-iota-coral.vercel.app/censor/bitwarden.png"></img> [Bitwarden](https://bitwarden.com/download/)

✔ Unlike LastPass, Bitwarden [does not store](https://www.reddit.com/r/Bitwarden/comments/104uuqx/moved_to_bitwarden_if_i_am_not_self_hosting_how/) addresses in a public format, and does not track the user
<br>
✔ As of May 2023, Bitwarden [had passed](https://bitwarden.com/help/is-bitwarden-audited/#2023-network-security-assessment) the SOC 2 Type 2 and SOC 3 requirements, as well as tests from Cure53
<br>
❌ Has some [problems](https://bauinvest.su/opublikovany-rezultaty-audita-bezopasnosti/) that were later fixed
<br>
❌ Bitwarden uses third-party vulnerable servers [Microsoft Azure](https://community.bitwarden.com/t/recent-ms-azure-server-vulnerabilities-and-bitwarden-data/49499)
<br>
❌ [Autofill](https://startpack.ru/articles/20230310-bitwarden) is best turned off

### <img width=20px src="https://site-iota-coral.vercel.app/censor/keepassxc.png"></img> [KeePassXC](https://github.com/keepassxreboot/keepassxc)

### <img width=20px src="https://raw.githubusercontent.com/Kunzisoft/KeePassDX/master/art/icon.png"></img> [KeePassDX](https://github.com/Kunzisoft/KeePassDX)

### <img width=20px src="https://site-iota-coral.vercel.app/censor/lesspass.png"></img> [LessPass](https://lesspass.com)

### <img width=20px src="https://site-iota-coral.vercel.app/censor/proton.webp"></img> [Proton Pass](https://proton.me/pass)

❌ **В России не работает без VPN! Синхронизация сломана!**

<h3 align="center">🛡 Protecting sites from recovery</h3>

Many sites offer convenient ways to recover by phone number only, however, which greatly reduces security. Here is a brief summary of the different sites.

Site | 📱 Mandatory phone number | 🔓 Restore by password | 🔓 Recovery by phone number | 🔑 Yubikey login
------------ | ---- | ---- | ---- | ---
Discord | ✔ No | ✔ No | ➖ Optional | ✔ Yes
Google | ✔ No | ✔ No | ➖ Optional | ✔ Yes
GitHub | ✔ No | ✔ No | ➖ Optional | ✔ Yes
SimpleLogin | ✔ No | ✔ No | ➖ Optional | ✔ Yes
VK  | ❌ Yes | ❌ Yes | ❌ Yes | ✔ Yes
Yandex  | ❌ Yes | ✔ No | ❌ Yes | ✔ Yes
