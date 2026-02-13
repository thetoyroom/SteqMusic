# SteqMusic Instances

This document lists public instances of SteqMusic that you can use. Instances are community-hosted versions of SteqMusic that provide access to the application.

---

## Official Instance

The official SteqMusic instance maintained by the core team:

| URL                                                    | Status   | Notes            |
| ------------------------------------------------------ | -------- | ---------------- |
| [steqmusic.tf](https://steqmusic.tf)                 | Official | Primary instance |
| [steqmusic.samidy.com](https://steqmusic.samidy.com) | Official | Secondary mirror |

---

## Community Instances

### UI-Only Instances

These instances provide the tidal-ui web interface, not SteqMusic:

| Provider            | URL                                            | Status    |
| ------------------- | ---------------------------------------------- | --------- |
| **bini (tidal-ui)** | [music.binimum.org](https://music.binimum.org) | Community |
| **squid.wtf**       | [tidal.squid.wtf](https://tidal.squid.wtf)     | Community |
| **QQDL**            | [tidal.qqdl.site](https://tidal.qqdl.site/)    | Community |

---

## API Instances

SteqMusic uses the Hi-Fi API under the hood. These are available API endpoints that can be used with SteqMusic or other Hi-Fi based applications:

### Official & Community APIs

| Provider          | URL                                 | Notes                                                      |
| ----------------- | ----------------------------------- | ---------------------------------------------------------- |
| **SteqMusic**     | `https://steqmusic-api.samidy.com`  | Official API - [See Note](https://rentry.co/steqmusicapi)  |
|                   | `https://api.steqmusic.tf`          | Official API                                               |
|                   | `https://arran.steqmusic.tf`        | Official API                                               |
| **squid.wtf**     | `https://triton.squid.wtf`          | Community hosted                                           |
| **Lucida (QQDL)** | `https://wolf.qqdl.site`            | Community hosted                                           |
|                   | `https://maus.qqdl.site`            | Community hosted                                           |
|                   | `https://vogel.qqdl.site`           | Community hosted                                           |
|                   | `https://katze.qqdl.site`           | Community hosted                                           |
|                   | `https://hund.qqdl.site`            | Community hosted                                           |
| **Spotisaver**    | `https://hifi-one.spotisaver.net`   | Community hosted                                           |
|                   | `https://hifi-two.spotisaver.net`   | Community hosted                                           |
| **Kinoplus**      | `https://tidal.kinoplus.online`     | Community hosted                                           |
| **Binimum**       | `https://tidal-api.binimum.org`     | Community hosted                                           |

---

## Instance Health

To check the current status of instances:

1. Visit the instance URL in your browser
2. Check if the page loads correctly
3. Try playing a track to verify API connectivity

> **Note:** Community instances may have varying uptime and performance. If one doesn't work, try another.

---

## Adding Your Instance

Want to add your instance to this list?

1. Ensure your instance is stable and publicly accessible
2. Open a pull request with your instance details
3. Include:
    - Instance URL
    - Provider name
    - Type (UI/API/Both)
    - Brief description

---

## Disclaimer

- Community instances are not affiliated with the official SteqMusic project
- Use at your own risk
- Instance availability and performance may vary
- The official project does not guarantee uptime for community instances

---

## Related Resources

- [Self-Hosting Guide](self-hosted-database.md) - Host your own instance
- [Contributing Guide](CONTRIBUTE.md) - Contribute to the project
- [Main Repository](https://github.com/thetoyroom/SteqMusic) - Source code
