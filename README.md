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
  * <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzMiAzMiIgd2lkdGg9IjMyIj4KICAgIDxwYXRoIGQ9Ik0yMC4xMDIgMTYuMmwuMDk3IDIuMy0xLjU5NyAzLTIuNSA0Ljg5OC0uNSA0LjEwMiAxLjc5NiA1LjggNC4xMDIgMi4zMDJoNi4ybDUuOC00LjQwMyAyLjYwMi02Ljg5OC02LTcuMzAxLTEuNzA0LTQuMTAyeiIgZmlsbD0iI2VjZWZmMSIvPgogICAgPHBhdGggZD0iTTM0LjMgMjEuODk4Yy0xLjYtMi4yOTYtMi45MDItMy42OTktMy42LTYuNTk3LS43LTIuOTAzLjE5OC0yLjEwMi0uNC00LjYwMkMzMCA5LjQgMjkuNSA4LjUgMjkgNy44MDFjLS42MDItLjctMS4zLTEuMTAyLTEuNy0xLjItLjkwMi0uNS0zLTEuMy01LjYuMDk4LTIuNyAxLjQwMy0yLjQgNC40MDMtMS45IDEwLjUgMCAuNDAzLS4xLjkwMy0uMyAxLjMwMS0uMzk4Ljg5OC0xLjEwMiAxLjctMS43IDIuMzk4LS42OTggMS0xLjQwMiAyLTEuOTAyIDMuMTAyLTEuMTk5IDIuMy0yLjI5NiA1LjItMiA2LjMuNS0uMSA2LjgwMSA5LjUgNi44MDEgOS43LjQwMy0uMTAyIDIuMTAyLS4xMDIgMy42MDItLjEwMiAyLjA5Ny0uMDk3IDMuMy0uMTk5IDUgLjIwNCAwLS4zMDEtLjEwMi0uNjAyLS4xMDItLjkwMyAwLS41OTcuMTAyLTEuMDk3LjItMS44LjEwMS0uNS4yMDMtMSAuMy0xLjU5OC0xIC44OTgtMi44IDEuODk4LTQuNSAyLjE5OS0xLjUuMy00LS4yLTUuMTk5LTEuNy4xMDIgMCAuMyAwIC4zOTgtLjEuMzAxLS4wOTguNjAyLS4yLjcwNC0uNC4yOTYtLjUuMDk3LTEtLjEwMi0xLjMtLjItLjMtMS43LTEuMzk4LTIuMzk4LTItLjcwNC0uNjAyLTEuMTAyLS44OTgtMS41LTEuMyAwIDAtLjYwMi0uNTk4LS44MDEtLjgwMi0uMi0uMTk5LS4zMDEtLjM5OC0uNDAzLS41LS4xOTktLjUtLjI5Ni0xLjA5Ny0uMTk5LTEuODk4LjEwMi0xLjEwMi41LTIgMS0zIC4yLS4zOTguNy0xLjIuNy0xLjJzLTEuNyA0LjItLjc5NyA1LjVjMCAwIC4wOTctMS4zLjUtMi42LjI5Ni0uOS43OTYtMi4yIDEuMzk4LTIuOS42MDItLjY5OCAyLjEwMi0zLjMgMi4yLTQuOTAyIDAtLjY5OS4xLTEuMzk4LjEtMS44OTgtLjQwMi0uMzk4IDYuNTk4LTEuMzk4IDctLjMuMDk4LjQwMiAxLjUgNCAyLjMwMiA1LjkwMkMzMC41IDIzLjUgMzEgMjQuMyAzMS4zIDI1LjNjLjMgMS4wOTcuNSAyLjU5Ny41IDQuMDk3IDAgLjMwMSAwIC44MDEtLjEwMiAxLjMwMS4yIDAgNC4xMDItNC4xOTktLjUtNy42OTkgMCAwIDIuODAxIDEuMyAyLjkwMyAzLjg5OC4wOTcgMi4xMDItLjgwMSAzLjgwMS0xIDQuMTAyLjA5NyAwIDIuMDk3Ljg5OCAyLjE5OS44OTguMzk4IDAgMS4xOTktLjI5NiAxLjE5OS0uMjk2LjEwMi0uMzAxLjM5OC0xLjEwMi4zOTgtMS40MDMuNzA0LTIuMy0xLTYtMi41OTctOC4zeiIgZmlsbD0iIzI2MzIzOCIvPgogICAgPHBhdGggZD0iTTIyLjg5OCAxMy4zYzAtMS4xMDUtLjU4Mi0yLTEuMjk2LTItLjcyIDAtMS4zMDEuODk1LTEuMzAxIDIgMCAxLjEwNi41ODIgMiAxLjMgMiAuNzE1IDAgMS4yOTctLjg5NCAxLjI5Ny0yek0yNy44IDEzLjJjMC0xLjI3LS43Ni0yLjMwMi0xLjY5OC0yLjMwMi0uOTQyIDAtMS43MDQgMS4wMzItMS43MDQgMi4zMDEgMCAxLjI3Ljc2MiAyLjMwMSAxLjcwNCAyLjMwMS45MzcgMCAxLjY5OS0xLjAzMSAxLjY5OS0yLjN6IiBmaWxsPSIjZWNlZmYxIi8+CiAgICA8cGF0aCBkPSJNMjEuNDggMTIuMzM2Yy0uMzgyLjA0Ny0uNjI1LjYxNy0uNTQzIDEuMjc3LjA4My42NTcuNDYxIDEuMTQ5Ljg0NCAxLjEwMi4zODMtLjA0Ny42My0uNjIxLjU0Ny0xLjI3Ny0uMDg2LS42NTctLjQ2NS0xLjE1My0uODQ4LTEuMTAyek0yNyAxMy42MDJjMC0uNzItLjQ1LTEuMzAxLTEtMS4zMDFzLTEgLjU4Mi0xIDEuM2MwIC43MTUuNDUgMS4yOTcgMSAxLjI5N3MxLS41ODIgMS0xLjI5NnoiIGZpbGw9IiMyMTIxMjEiLz4KICAgIDxwYXRoIGQ9Ik0zOS4zIDM1LjYwMmMtLjQwMi0uMjA0LTEuMS0uNS0xLjY5OC0xLjQwMy0uMzAxLS41LS4yMDQtMS44OTgtLjcwNC0yLjUtLjI5Ni0uMzk4LS42OTktLjE5OS0uNzk2LS4xOTktLjkwMy4yLTMgMS42MDItNC40MDMgMC0uMTk5LS4yLS41LS41LTEtLjVzLS42OTkuMi0uODk4LjYwMmMtLjIuMzk4LS4yLjY5OS0uMiAxLjY5OSAwIC44IDAgMS42OTktLjEwMSAyLjM5OC0uMiAxLjctLjUgMi43LS41IDMuNyAwIDEuMTAxLjMgMS44LjcgMi4xMDEuMy4zLjguNSAxLjkwMi41IDEuMDk3IDAgMS43OTYtLjM5OCAyLjUtMS4xMDIuNS0uNS44OTgtLjY5OSAyLjI5Ni0xLjY5OUMzNy41IDM4LjUgMzkuMiAzNy42MDIgMzkuNSAzNy4zMDFjLjItLjIuNS0uMzAxLjUtLjkwMyAwLS41LS4zOTgtLjY5OS0uNy0uNzk2ek0xOS4yIDM1Ljg5OEMxOC4yIDM0LjMwMSAxOC4xMDEgMzQgMTcuMzk3IDMzYy0uNTk3LTEtMS44OTgtMi44OTgtMi42OTktMi44OTgtLjU5NyAwLS44OTguMjk2LTEuMy42OTktLjM5OS4zOTgtLjc5NyAxLjMtMS41IDEuOC0uNTk4LjUtMi4yOTcuMzk5LTIuNyAxLS4zOTguNTk4LjQwMyAxLjUuNDAzIDMgMCAuNTk4LS41IDEtLjYwMiAxLjM5OS0uMTAyLjUtLjIuOCAwIDEuMi4zOTguNi44OTguOCA0LjMgMS41IDEuODAyLjQwMiAzLjUgMS40MDIgNC41OTggMS41IDEuMTAyLjEgMyAwIDMtMi43LjEwMi0xLjYwMi0uNzk2LTItMS42OTktMy42MDJ6TTIxLjEwMiAxNy44QzIwLjUgMTcuMzk5IDIwIDE3IDIwIDE2LjM5OWMwLS41OTcuMzk4LS43OTYgMS0xLjI5NkMyMS4xMDIgMTUgMjIuMiAxNCAyMy4zIDE0YzEuMDk4IDAgMi40LjcgMi45Ljg5OC45MDIuMjA0IDEuOC40MDMgMS42OTggMS4xMDItLjA5NyAxLS4xOTkgMS4yLTEuMTk5IDEuNy0uNjk5LjE5OC0yIDEuMy0yLjg5OCAxLjMtLjQwMyAwLTEgMC0xLjQwMy0uMTAyLS4yOTYtLjA5Ny0uNzk2LS41OTctMS4yOTYtMS4wOTd6IiBmaWxsPSIjZmZjMTA3Ii8+CiAgICA8cGF0aCBkPSJNMjAuODk4IDE3Yy4yMDQuMi41LjM5OC44MDEuNS4yLjEwMi41LjIuNS4yaC45MDNjLjUgMCAxLjE5OS0uMiAxLjg5OC0uNTk4LjctLjMwMS44LS41IDEuMy0uNzA0LjUtLjI5NiAxLS41OTcuODAyLS42OTktLjIwNC0uMDk3LS40MDMgMC0xLjEwMi40MDMtLjYwMi4zOTgtMS4xMDIuNTk3LTEuNy44OTgtLjMuMTAyLS42OTguMy0xIC4zaC0uOTAyYy0uMjk2IDAtLjUtLjEtLjc5Ni0uMTk4LS4yMDQtLjEwMi0uMzAxLS4yMDQtLjQwMy0uMjA0LS4xOTktLjA5Ny0uNTk3LS41LS44LS41OTcgMCAwLS4yIDAtLjA5OC4wOTcuMy4zMDEuMzk4LjQwMy41OTcuNjAyek0yMy44OTggMTQuOGMuMTAyLjIuMzAxLjIuNDAzLjMwMi4wOTcuMDk3LjE5OS4wOTcuMTk5LjA5Ny4xMDItLjA5NyAwLS4zLS4xMDItLjMgMC0uMi0uNS0uMi0uNS0uMDk4ek0yMi4zIDE1YzAgLjEwMi4yLjIuMi4xMDIuMTAyLS4xMDIuMi0uMjA0LjMtLjIwNC4yLS4wOTcuMDk4LS4xOTktLjE5OC0uMTk5LS4yMDQuMTAyLS4yMDQuMi0uMzAxLjMwMXoiIGZpbGw9IiM2MzQ3MDMiLz4KICAgIDxwYXRoIGQ9Ik0zMiAzMi43di4zYy4yLjM5OC43LjUgMS4xMDIuNS41OTcgMCAxLjE5OS0uMzk4IDEuNS0uOCAwLS4wOTguMDk3LS4yLjE5OS0uMzAyLjE5OS0uMjk2LjMtLjUuMzk4LS41OTcgMCAwLS4wOTctLjEwMi0uMDk3LS4yLS4xMDItLjIwMy0uNDAzLS40MDItLjgwMS0uNS0uMzAxLS4xMDEtLjgwMS0uMjAzLTEtLjIwMy0uOTAzLS4wOTctMS40MDMuMjA0LTEuNy41IDAgMCAuMDk4IDAgLjA5OC4xMDIuMi4yLjMwMS4zOTguMzAxLjcuMTAyLjE5OCAwIC4zIDAgLjV6IiBmaWxsPSIjNDU1YTY0Ii8+Cjwvc3ZnPgo=" alt="Linux" />[NodeJS server for Linux](tg://resolve?domain=MTProxy&post=72) & [for Windows](tg://resolve?domain=MTProxy&post=85) by <b>FreedomPrevails</b>
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
