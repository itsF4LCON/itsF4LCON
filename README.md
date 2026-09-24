<a href="https://xivlabs.tech">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img alt="F4LCON: security tools and things that run at the edge" src="assets/banner-light.svg" width="100%">
  </picture>
</a>

<p align="center">
  <a href="https://xivlabs.tech/#attacks"><img alt="hive attacks in the last 24h" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhive.xivlabs.tech%2Fstats&query=%24.total_24h&label=attacks%20caught%20%C2%B7%2024h&color=ef4444&labelColor=0c0a09&style=flat-square"></a>
  <a href="https://xivlabs.tech/#attacks"><img alt="unique attacking IPs in the last 24h" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhive.xivlabs.tech%2Fstats&query=%24.unique_sources_24h&label=unique%20IPs&color=a8a29e&labelColor=0c0a09&style=flat-square"></a>
  <a href="https://xivlabs.tech/#attacks"><img alt="most tried password" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhive.xivlabs.tech%2Fstats&query=%24.top_passwords%5B0%5D.k&label=top%20password&color=5d574e&labelColor=0c0a09&style=flat-square"></a>
</p>

<p align="center"><sub>Live from <a href="https://github.com/itsF4LCON/hive">hive</a>, my honeypot. Every number above is someone trying to break in.</sub></p>

### Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <b><a href="https://github.com/itsF4LCON/aps">aps</a></b> <sub>Rust</sub><br>
      Edge anti-phishing scanner that judges a link in under 15ms.<br>
      <sub><a href="https://xivlabs.tech/#aps-demo">Try it</a></sub>
    </td>
    <td width="33%" valign="top">
      <b><a href="https://github.com/itsF4LCON/hive">hive</a></b> <sub>Rust</sub><br>
      SSH/HTTP honeypot that lets no one in and maps every attempt.<br>
      <sub><a href="https://xivlabs.tech/#attacks">Attack map</a> · <a href="https://xivlabs.tech/reports">Reports</a></sub>
    </td>
    <td width="33%" valign="top">
      <b><a href="https://github.com/itsF4LCON/hive-blocklist">hive-blocklist</a></b> <sub>Python</sub><br>
      Self-updating blocklist of the IPs attacking hive, rebuilt weekly.<br>
      <sub><a href="https://github.com/itsF4LCON/hive-blocklist/tree/main/lists">Get the list</a></sub>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <b><a href="https://github.com/itsF4LCON/postburn">postburn</a></b> <sub>Rust</sub><br>
      One-time secret links. The server never sees the key.<br>
      <sub><a href="https://burn.xivlabs.tech">Send a secret</a></sub>
    </td>
    <td width="33%" valign="top">
      <b><a href="https://github.com/itsF4LCON/desk">desk</a></b> <sub>Rust</sub><br>
      Your Linux desktop in any browser, 1080p60 over WebRTC.<br>
      <sub>Self-hosted</sub>
    </td>
    <td width="33%" valign="top">
      <b><a href="https://github.com/itsF4LCON/dealbreaker">dealbreaker</a></b> <sub>Rust</sub><br>
      Card game for 2-8 friends where special cards start mini-games.<br>
      <sub><a href="https://dealbreaker.xivlabs.tech">Play now</a></sub>
    </td>
  </tr>
</table>

### Stack

<img alt="Rust, Python, JavaScript, Swift, C#, Cloudflare, Linux" src="https://skillicons.dev/icons?i=rust,py,js,swift,cs,cloudflare,linux&theme=dark" height="40">

<sub>Cloudflare Workers · Durable Objects · D1 · KV · Tunnel · Access</sub>
