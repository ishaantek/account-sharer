# Account Sharer
The most powerful account sharer for Chrome 💎 <br><br>
[Get it now - it's free!](https://chrome.google.com/webstore/detail/account-sharer/ickmhacpabgcbnefffalhfodifihmnfa)

Account Sharer is a Chrome Extension to share your account **without** giving out your **password**.

Made by [Ishaan Garg](https://www.ishaantek.com)

<a href="https://www.producthunt.com/posts/account-sharer?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-account-sharer" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=323123&theme=dark" alt="Account Sharer - Share your account without giving out your password. | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

## Table of contents
- [Account Sharer](#account-sharer)
  - [Table of contents](#table-of-contents)
  - [Use](#use)
  - [How it works](#how-it-works)
## Use

1. Ask the recipient for their code (found on the extension menu `RECEIVE ACCOUNT`) 
2. Go to the site from where you want to share the account and click the extension icon.
3. Press `SHARE ACCOUNT` and enter the code with an optional timeout.
4. Press `SHARE` and copy the result.
5. The recipient, still on the `RECEIVE ACCOUNT`, menu pastes the text on the `Share result` textbox and presses the `RECEIVE` button.

:tophat:
**Voilà**

## How it works

The extension uses the Standford Javascript Crypto Lib implementation of EC-ElGamal. It generates a new public-private key combination for each extension upon first use and uses it to encrypt/decrypt the session.

Appart for the keys, it doesn't store anything more than the URL/title of the sessions stored (to show them on the `ACCOUNT HISTORY` menu).

If you want to be extra careful, you can always regenerate your keys on the extension.

#
 Feel free to reach out to me through email at ishaan@ishaantek.com or [on Twitter](https://twitter.com/ishaantek) if you have any questions or feedback! Hope you find this useful 💙
