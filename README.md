# MTProto & SOCKS5 Telegram proxies
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

## Build your own proxy server
* **MTProto:**
  * <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA0OCA0OCI+PHBhdGggZD0iTTIwLjEwMiAxNi4ybC4wOTcgMi4zLTEuNTk3IDMtMi41IDQuODk4LS41IDQuMTAyIDEuNzk2IDUuOCA0LjEwMiAyLjMwMmg2LjJsNS44LTQuNDAzIDIuNjAyLTYuODk4LTYtNy4zMDEtMS43MDQtNC4xMDJ6IiBmaWxsPSIjZWNlZmYxIi8+PHBhdGggZD0iTTM0LjMgMjEuODk4Yy0xLjYtMi4yOTYtMi45MDItMy42OTktMy42LTYuNTk3LS43LTIuOTAzLjE5OC0yLjEwMi0uNC00LjYwMkE3Ljg0MyA3Ljg0MyAwIDAgMCAyOSA3LjgwMWMtLjYwMi0uNy0xLjMtMS4xMDItMS43LTEuMi0uOTAyLS41LTMtMS4zLTUuNi4wOTgtMi43IDEuNDAzLTIuNCA0LjQwMy0xLjkgMTAuNSAwIC40MDMtLjEuOTAzLS4zIDEuMzAxLS4zOTguODk4LTEuMTAyIDEuNy0xLjcgMi4zOTgtLjY5OCAxLTEuNDAyIDItMS45MDIgMy4xMDItMS4xOTkgMi4zLTIuMjk2IDUuMi0yIDYuMy41LS4xIDYuODAxIDkuNSA2LjgwMSA5LjcuNDAzLS4xMDIgMi4xMDItLjEwMiAzLjYwMi0uMTAyIDIuMDk3LS4wOTcgMy4zLS4xOTkgNSAuMjA0IDAtLjMwMS0uMTAyLS42MDItLjEwMi0uOTAzIDAtLjU5Ny4xMDItMS4wOTcuMi0xLjguMTAxLS41LjIwMy0xIC4zLTEuNTk4LTEgLjg5OC0yLjggMS44OTgtNC41IDIuMTk5LTEuNS4zLTQtLjItNS4xOTktMS43LjEwMiAwIC4zIDAgLjM5OC0uMS4zMDEtLjA5OC42MDItLjIuNzA0LS40LjI5Ni0uNS4wOTctMS0uMTAyLTEuMy0uMi0uMy0xLjctMS4zOTgtMi4zOTgtMi0uNzA0LS42MDItMS4xMDItLjg5OC0xLjUtMS4zIDAgMC0uNjAyLS41OTgtLjgwMS0uODAyLS4yLS4xOTktLjMwMS0uMzk4LS40MDMtLjUtLjE5OS0uNS0uMjk2LTEuMDk3LS4xOTktMS44OTguMTAyLTEuMTAyLjUtMiAxLTMgLjItLjM5OC43LTEuMi43LTEuMnMtMS43IDQuMi0uNzk3IDUuNWMwIDAgLjA5Ny0xLjMuNS0yLjYuMjk2LS45Ljc5Ni0yLjIgMS4zOTgtMi45LjYwMi0uNjk4IDIuMTAyLTMuMyAyLjItNC45MDIgMC0uNjk5LjEtMS4zOTguMS0xLjg5OC0uNDAyLS4zOTggNi41OTgtMS4zOTggNy0uMy4wOTguNDAyIDEuNSA0IDIuMzAyIDUuOTAyQzMwLjUgMjMuNSAzMSAyNC4zIDMxLjMgMjUuM2MuMyAxLjA5Ny41IDIuNTk3LjUgNC4wOTcgMCAuMzAxIDAgLjgwMS0uMTAyIDEuMzAxLjIgMCA0LjEwMi00LjE5OS0uNS03LjY5OSAwIDAgMi44MDEgMS4zIDIuOTAzIDMuODk4LjA5NyAyLjEwMi0uODAxIDMuODAxLTEgNC4xMDIuMDk3IDAgMi4wOTcuODk4IDIuMTk5Ljg5OC4zOTggMCAxLjE5OS0uMjk2IDEuMTk5LS4yOTYuMTAyLS4zMDEuMzk4LTEuMTAyLjM5OC0xLjQwMy43MDQtMi4zLTEtNi0yLjU5Ny04LjN6IiBmaWxsPSIjMjYzMjM4Ii8+PHBhdGggZD0iTTIyLjg5OCAxMy4zYzAtMS4xMDUtLjU4Mi0yLTEuMjk2LTItLjcyIDAtMS4zMDEuODk1LTEuMzAxIDIgMCAxLjEwNi41ODIgMiAxLjMgMiAuNzE1IDAgMS4yOTctLjg5NCAxLjI5Ny0yem00LjkwMi0uMWMwLTEuMjctLjc2LTIuMzAyLTEuNjk4LTIuMzAyLS45NDIgMC0xLjcwNCAxLjAzMi0xLjcwNCAyLjMwMSAwIDEuMjcuNzYyIDIuMzAxIDEuNzA0IDIuMzAxLjkzNyAwIDEuNjk5LTEuMDMxIDEuNjk5LTIuM3oiIGZpbGw9IiNlY2VmZjEiLz48cGF0aCBkPSJNMjEuNDggMTIuMzM2Yy0uMzgyLjA0Ny0uNjI1LjYxNy0uNTQzIDEuMjc3LjA4My42NTcuNDYxIDEuMTQ5Ljg0NCAxLjEwMi4zODMtLjA0Ny42My0uNjIxLjU0Ny0xLjI3Ny0uMDg2LS42NTctLjQ2NS0xLjE1My0uODQ4LTEuMTAyek0yNyAxMy42MDJjMC0uNzItLjQ1LTEuMzAxLTEtMS4zMDFzLTEgLjU4Mi0xIDEuM2MwIC43MTUuNDUgMS4yOTcgMSAxLjI5N3MxLS41ODIgMS0xLjI5NnoiIGZpbGw9IiMyMTIxMjEiLz48cGF0aCBkPSJNMzkuMyAzNS42MDJjLS40MDItLjIwNC0xLjEtLjUtMS42OTgtMS40MDMtLjMwMS0uNS0uMjA0LTEuODk4LS43MDQtMi41LS4yOTYtLjM5OC0uNjk5LS4xOTktLjc5Ni0uMTk5LS45MDMuMi0zIDEuNjAyLTQuNDAzIDAtLjE5OS0uMi0uNS0uNS0xLS41cy0uNjk5LjItLjg5OC42MDJjLS4yLjM5OC0uMi42OTktLjIgMS42OTkgMCAuOCAwIDEuNjk5LS4xMDEgMi4zOTgtLjIgMS43LS41IDIuNy0uNSAzLjcgMCAxLjEwMS4zIDEuOC43IDIuMTAxLjMuMy44LjUgMS45MDIuNSAxLjA5NyAwIDEuNzk2LS4zOTggMi41LTEuMTAyLjUtLjUuODk4LS42OTkgMi4yOTYtMS42OTlDMzcuNSAzOC41IDM5LjIgMzcuNjAyIDM5LjUgMzcuMzAxYy4yLS4yLjUtLjMwMS41LS45MDMgMC0uNS0uMzk4LS42OTktLjctLjc5NnptLTIwLjEuMjk2QzE4LjIgMzQuMzAxIDE4LjEwMSAzNCAxNy4zOTcgMzNjLS41OTctMS0xLjg5OC0yLjg5OC0yLjY5OS0yLjg5OC0uNTk3IDAtLjg5OC4yOTYtMS4zLjY5OS0uMzk5LjM5OC0uNzk3IDEuMy0xLjUgMS44LS41OTguNS0yLjI5Ny4zOTktMi43IDEtLjM5OC41OTguNDAzIDEuNS40MDMgMyAwIC41OTgtLjUgMS0uNjAyIDEuMzk5LS4xMDIuNS0uMi44IDAgMS4yLjM5OC42Ljg5OC44IDQuMyAxLjUgMS44MDIuNDAyIDMuNSAxLjQwMiA0LjU5OCAxLjUgMS4xMDIuMSAzIDAgMy0yLjcuMTAyLTEuNjAyLS43OTYtMi0xLjY5OS0zLjYwMnpNMjEuMTAyIDE3LjhDMjAuNSAxNy4zOTkgMjAgMTcgMjAgMTYuMzk5YzAtLjU5Ny4zOTgtLjc5NiAxLTEuMjk2QzIxLjEwMiAxNSAyMi4yIDE0IDIzLjMgMTRjMS4wOTggMCAyLjQuNyAyLjkuODk4LjkwMi4yMDQgMS44LjQwMyAxLjY5OCAxLjEwMi0uMDk3IDEtLjE5OSAxLjItMS4xOTkgMS43LS42OTkuMTk4LTIgMS4zLTIuODk4IDEuMy0uNDAzIDAtMSAwLTEuNDAzLS4xMDItLjI5Ni0uMDk3LS43OTYtLjU5Ny0xLjI5Ni0xLjA5N3oiIGZpbGw9IiNmZmMxMDciLz48cGF0aCBkPSJNMjAuODk4IDE3Yy4yMDQuMi41LjM5OC44MDEuNS4yLjEwMi41LjIuNS4yaC45MDNjLjUgMCAxLjE5OS0uMiAxLjg5OC0uNTk4LjctLjMwMS44LS41IDEuMy0uNzA0LjUtLjI5NiAxLS41OTcuODAyLS42OTktLjIwNC0uMDk3LS40MDMgMC0xLjEwMi40MDMtLjYwMi4zOTgtMS4xMDIuNTk3LTEuNy44OTgtLjMuMTAyLS42OTguMy0xIC4zaC0uOTAyYy0uMjk2IDAtLjUtLjEtLjc5Ni0uMTk4LS4yMDQtLjEwMi0uMzAxLS4yMDQtLjQwMy0uMjA0LS4xOTktLjA5Ny0uNTk3LS41LS44LS41OTcgMCAwLS4yIDAtLjA5OC4wOTcuMy4zMDEuMzk4LjQwMy41OTcuNjAyem0zLTIuMmMuMTAyLjIuMzAxLjIuNDAzLjMwMi4wOTcuMDk3LjE5OS4wOTcuMTk5LjA5Ny4xMDItLjA5NyAwLS4zLS4xMDItLjMgMC0uMi0uNS0uMi0uNS0uMDk4ek0yMi4zIDE1YzAgLjEwMi4yLjIuMi4xMDIuMTAyLS4xMDIuMi0uMjA0LjMtLjIwNC4yLS4wOTcuMDk4LS4xOTktLjE5OC0uMTk5LS4yMDQuMTAyLS4yMDQuMi0uMzAxLjMwMXoiIGZpbGw9IiM2MzQ3MDMiLz48cGF0aCBkPSJNMzIgMzIuN3YuM2MuMi4zOTguNy41IDEuMTAyLjUuNTk3IDAgMS4xOTktLjM5OCAxLjUtLjggMC0uMDk4LjA5Ny0uMi4xOTktLjMwMi4xOTktLjI5Ni4zLS41LjM5OC0uNTk3IDAgMC0uMDk3LS4xMDItLjA5Ny0uMi0uMTAyLS4yMDMtLjQwMy0uNDAyLS44MDEtLjUtLjMwMS0uMTAxLS44MDEtLjIwMy0xLS4yMDMtLjkwMy0uMDk3LTEuNDAzLjIwNC0xLjcuNSAwIDAgLjA5OCAwIC4wOTguMTAyLjIuMi4zMDEuMzk4LjMwMS43LjEwMi4xOTggMCAuMyAwIC41eiIgZmlsbD0iIzQ1NWE2NCIvPjwvc3ZnPg==" alt="Linux" />[NodeJS server for Linux](tg://resolve?domain=MTProxy&post=72) & [for Windows](tg://resolve?domain=MTProxy&post=85) by <b>FreedomPrevails</b>
  * <a href="https://github.com/iShift/mtproxy/tree/d93f668a13af038603b2287df5ddc7142f25d1ca" target="_blank" alt="RUST/mio MTProxy">RUST/mio solution</a> by <b>dotcypress</b> *(\*nix)*  
  * [PHP version](tg://resolve?domain=MadelineProto&post=348) by <b>danog</b> *(\*nix)*  
  * <a href="https://github.com/TGMTProto/MTProtoProxy" target="_blank" alt="C# MTProxy">C# implementation</a> by <b>TGMTProto</b> *(Windows/Linux)*   
* **SOCKS5:**
  * <a href="https://www.inet.no/dante/" target="_blank" alt="SOCKS5 Proxy">Dante</a> by <b>Inferno Nettverk A/S</b> *(\*nix)*  

---

## Proxies list by various contributors
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

## Telegram apps download links
* <a href="https://rink.hockeyapp.net/apps/c6f5a76f5c364ac89a98b77671ef2d63" target="_blank" alt="iOS"><b>iOS</b><sup>β</sup> | <i>X</i></a>
* <a href="https://play.google.com/apps/testing/org.thunderdog.challegram/" target="_blank" alt="Android"><b>Android</b><sup>β</sup> | <i>X</i></a>
* <a href="https://rink.hockeyapp.net/apps/6ed2ac3049e1407387c2f1ffcb74e81f" target="_blank" alt="macOS"><b>macOS</b><sup>β</sup> | <i>Native</i></a>
* <a href="https://tdesktop.com/win/portable?alpha=1" target="_blank" alt="Windows Portable"><b>Windows</b><sup>α</sup> | <i>TDesktop portable</i></a>
* <a href="https://tdesktop.com/win/portable?alpha=1" target="_blank" alt="Linux"><b>Linux</b><sup>α</sup> | <i>TDesktop</i></a>

---

## Donate
<img src="https://img.shields.io/beerpay/hashdog/scrapfy-chrome-extension.svg?style=for-the-badge&label=🍺+BEERWARE&colorA=C39B76&colorB=568584" alt="BEERWARE" />

* <a href="bitcoin:13TaJ165Grj1VoHH4ZX6jtpvGscQZRvXic?amount=0.002&message=Thnx4TGProxy" target="_blank" alt="Bitcoin">Bitcoin

  <img src="https://a-u.me/0/smzx7.png" alt="Bitcoin"></a>
* <a href="https://paypal.me/Arxat/20" target="_blank" alt="PayPal">PayPal</a>
* <a href="https://ishop.qiwi.com/public/order/embed.action?from=553829&ccy=" target="_blank" alt="QIWI">QIWI</a>

---

## Contact & Support
Have any troubles?  
Check actual info in [my channel.](tg://resolve?domain=Syncrets)

<a href="https://a-u.me/contact/" target="_blank" alt="Contact">Contact me via other services.</a>
