## ![Proxy](https://a-u.me/img/github/encrypt32.svg) MTProto & SOCKS5 Telegram proxies
[![MTProxy Telegram](https://img.shields.io/badge/MTProxy-Telegram-2a9ed8.svg?longCache=true&style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQwIDI0MCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxkZWZzPgogICAgICAgIDxsaW5lYXJHcmFkaWVudCB4MT0iNjUuOTclIiB5MT0iNDMuNjklIiB4Mj0iODUuMTIlIiB5Mj0iODAuMjQlIiBpZD0ibGluZWFyR3JhZGllbnQtMSI+CiAgICAgICAgICAgIDxzdG9wIHN0b3AtY29sb3I9IiNFRkY3RkMiIG9mZnNldD0iMCUiPjwvc3RvcD4KICAgICAgICAgICAgPHN0b3Agc3RvcC1jb2xvcj0iI0ZGRkZGRiIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+CiAgICAgICAgPC9saW5lYXJHcmFkaWVudD4KICAgIDwvZGVmcz4KCQk8cGF0aCBkPSJNODUuMjk4NzU4NCwxNzguMzkwNDk0IEM3OC41NjM5OTQ4LDE3OC4zOTA0OTQgNzkuNzA4Mzk4OCwxNzUuODQ4MTY5IDc3LjM4NTYzNjQsMTY5LjQzNzE5NiBMNTcuNTgwODMwMiwxMDQuMjczNCBMMjEwLjAyOTQzNiwxMy44NTU1NzIzIiBmaWxsPSIjQzhEQUVBIj48L3BhdGg+CgkJPHBhdGggZD0iTTg1LjI5ODc1ODQsMTc4LjM5MDQ5NCBDOTAuNDk1ODcsMTc4LjM5MDQ5NCA5Mi43OTIxMjcxLDE3Ni4wMTQyNjMgOTUuNjkyOTgxNiwxNzMuMTk0NjU0IEwxMjMuNDEwOTEsMTQ2LjI0OTAzIEw4OC44MzYyNTksMTI1LjQwNTA1MyIgZmlsbD0iI0E5QzlERCI+PC9wYXRoPgoJCTxwYXRoIGQ9Ik04OC44MzI3OTQzLDEyNS40MTAyNDkgTDE3Mi42MTAyMzMsMTg3LjI5MDk2NyBDMTgyLjE3MDMxOSwxOTIuNTY0NTcxIDE4OS4wNzAxNzgsMTg5LjgzNDE1NyAxOTEuNDUxNDk0LDE3OC40MTczMzkgTDIyNS41NTMyMDgsMTcuNzU2NzgxOSBDMjI5LjA0NDYyNywzLjc2MjMwNzQ3IDIyMC4yMTczMzMsLTIuNTg0OTMwMjEgMjExLjA3MTYzLDEuNTY2MTk5MjYgTDEwLjgyNjkyMTcsNzguNzYwNzg4NSBDLTIuODQxNjU0OTQsODQuMjQxODc5NyAtMi43NjE5NjU5LDkxLjg2NTczNTIgOC4zMzU0MjY0LDk1LjI2Mjc3NTIgTDU5LjcyMjczMzEsMTExLjI5NzY1NiBMMTc4LjY4OTgxNCwzNi4yNjEwNzE5IEMxODQuMzA1OTg2LDMyLjg1NjIzODIgMTg5LjQ2MDQ4MSwzNC42ODY3NDk5IDE4NS4yMjk4NTksMzguNDQwNTUzNSIgZmlsbD0idXJsKCNsaW5lYXJHcmFkaWVudC0xKSI+PC9wYXRoPgo8L3N2Zz4K&colorA=99B7CC)](tg://resolve?domain=Syncrets)  

Feel free to use [native MTProto](tg://proxy?server=62.210.73.58&port=143&secret=9615e2fc5c8c17419a8055ca5b55e9dd) proxy and [old stable SOCKS5](tg://socks?server=62.210.73.58&port=123&user=prx&pass=hHQ0nVmI2kI4Gf52OZhULAQI) one to connect Telegram *(Telegram Open Network / Open Network in future):*

* [MTProto Proxy](tg://proxy?server=62.210.73.58&port=143&secret=9615e2fc5c8c17419a8055ca5b55e9dd)
* [SOCKS5 Proxy](tg://socks?server=62.210.73.58&port=123&user=prx&pass=hHQ0nVmI2kI4Gf52OZhULAQI)


<details>

<summary>
<b>
Changelog
</b>
</summary>

<p>
<h5>1.0.2 (March 27, 2018)</h5>
<ul>
<li>Changed <b>MTProto</b> server backend from unstable <b>RUST/mio</b> to <b>NodeJS</b></li>
<li>Added <b>your own server</b> instructions links for <i>*nix/Windows</i></li>
</ul>

<h5>1.0.1 (May 25, 2018)</h5>
<ul>
<li><b>SOCKS5</b> proxy port mapped to <b>123</b> <i>(default for NTP service)</i></li>
<li><b>MTProto</b> port mapped to <b>143</b> <i>(default for IMAP service)</i></li>
<li>Changed <b>MTProto</b> server backend from overloading <b>PHP</b> to <b>RUST/mio</b></li>
</ul>

<h5>1.0.0 (May 24, 2018)</h5>
<ul>
<li>Project started</li>
</ul>
</p>

</details>

---

### ![Build](https://a-u.me/img/github/code32.svg) Build your own proxy server
* **MTProto:**
  * ![Linux](https://a-u.me/img/github/24lin.svg) ![Windows](https://a-u.me/img/github/24win.svg) ![NodeJS](https://a-u.me/img/github/24node.svg) [NodeJS server for Linux](tg://resolve?domain=MTProxy&post=72) & [for Windows](tg://resolve?domain=MTProxy&post=85) by <b>FreedomPrevails</b>
  * ![Linux](https://a-u.me/img/github/24lin.svg) ![macOS](https://a-u.me/img/github/24ios.svg) <a href="https://github.com/iShift/mtproxy/tree/d93f668a13af038603b2287df5ddc7142f25d1ca" target="_blank" alt="RUST/mio MTProxy">RUST/mio solution</a> by <b>dotcypress</b> *(\*nix)*  
  * ![Linux](https://a-u.me/img/github/24lin.svg) ![macOS](https://a-u.me/img/github/24ios.svg) ![PHP](https://a-u.me/img/github/24php.svg) [PHP version](tg://resolve?domain=MadelineProto&post=348) by <b>danog</b> *(\*nix)*  
  * ![Linux](https://a-u.me/img/github/24lin.svg) ![Windows](https://a-u.me/img/github/24win.svg) ![C#](https://a-u.me/img/github/24csharp.svg) <a href="https://github.com/TGMTProto/MTProtoProxy" target="_blank" alt="C# MTProxy">C# implementation</a> by <b>TGMTProto</b> *(Windows/Linux)*   
* **SOCKS5:**
  * ![Linux](https://a-u.me/img/github/24lin.svg) ![macOS](https://a-u.me/img/github/24ios.svg) <a href="https://www.inet.no/dante/" target="_blank" alt="SOCKS5 Proxy">Dante</a> by <b>Inferno Nettverk A/S</b> *(\*nix)*  

---

### ![List](https://a-u.me/img/github/list32.svg) Proxies list by various contributors
<details>
<summary>
<b>
MTProto
</b>
</summary>

<p>
<ul>
<li><a href="#" target="_blank" alt="MTProxies list">Coming soon</a></li>
</ul>
</p>

</details>

<details>
<summary>
<b>
SOCKS5
</b>
</summary>

<p>
<ul>
<li><a href="#" target="_blank" alt="MTProxies list">Coming soon</a></li>
</ul>  
</p>

</details>

---

### ![Apps](https://a-u.me/img/github/tg32.svg) Telegram apps download links
* ![iOS](https://a-u.me/img/github/24ios.svg) <a href="https://rink.hockeyapp.net/apps/c6f5a76f5c364ac89a98b77671ef2d63" target="_blank" alt="iOS"><b>iOS</b><sup>β</sup> | <i>X</i></a>
* ![Android](https://a-u.me/img/github/24android.svg) <a href="https://play.google.com/apps/testing/org.thunderdog.challegram/" target="_blank" alt="Android"><b>Android</b><sup>β</sup> | <i>X</i></a>
* ![macOS](https://a-u.me/img/github/24imacos.svg) <a href="https://rink.hockeyapp.net/apps/6ed2ac3049e1407387c2f1ffcb74e81f" target="_blank" alt="macOS"><b>macOS</b><sup>β</sup> | <i>Native</i></a>
* ![Windows](https://a-u.me/img/github/24win.svg) <a href="https://tdesktop.com/win/portable?alpha=1" target="_blank" alt="Windows Portable"><b>Windows</b><sup>α</sup> | <i>TDesktop portable</i></a>
* ![Linux](https://a-u.me/img/github/24lin.svg) <a href="https://tdesktop.com/win/portable?alpha=1" target="_blank" alt="Linux"><b>Linux</b><sup>α</sup> | <i>TDesktop</i></a>

---

### ![Donate](https://a-u.me/img/github/btc32.svg) Donate
<img src="https://img.shields.io/beerpay/hashdog/scrapfy-chrome-extension.svg?style=for-the-badge&label=🍺+BEERWARE&colorA=C39B76&colorB=568584" alt="BEERWARE" />

* <a href="bitcoin:13TaJ165Grj1VoHH4ZX6jtpvGscQZRvXic?amount=0.002&message=Thnx4TGProxy" target="_blank" alt="Bitcoin">Bitcoin

  <img src="https://a-u.me/0/smzx7.png" alt="Bitcoin"></a>
* <a href="https://paypal.me/Arxat/20" target="_blank" alt="PayPal">PayPal</a>
* <a href="https://ishop.qiwi.com/public/order/embed.action?from=553829&ccy=" target="_blank" alt="QIWI">QIWI</a>

---

### ![Contact](https://a-u.me/img/github/contact32.svg) Contact & Support
Have any troubles?  
Check actual info in [my channel.](tg://resolve?domain=Syncrets)

<a href="https://a-u.me/contact/" target="_blank" alt="Contact">Contact me via other services.</a>
