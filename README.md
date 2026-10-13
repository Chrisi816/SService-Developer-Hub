<div align="center">

# S-SERVICE · DEVELOPER HUB

**Integration examples, API references and developer resources for S-Service FiveM products.**

[![Lua](https://img.shields.io/badge/Language-Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](https://www.lua.org/)
[![FiveM](https://img.shields.io/badge/Platform-FiveM-F40552?style=for-the-badge)](https://fivem.net/)
[![Examples](https://img.shields.io/badge/Examples-5-17A2B8?style=for-the-badge)](#example-library)

[**Browse examples**](#example-library) · [**Store**](https://s-service.tebex.io/) · [**Discord support**](https://discord.gg/s-service)

---

*Build integrations faster. Keep your resources connected.*

</div>

## Overview

Welcome to the **S-Service Developer Hub** — a collection of practical Lua integration examples for S-Service resources on FiveM.

Use these snippets as a starting point when connecting existing scripts to S-Service systems. Each file focuses on a specific product or product generation and demonstrates available integration calls.

> [!IMPORTANT]
> These are **reference snippets**, not standalone resources. The corresponding S-Service product must be installed and configured. Check the API of your installed product version before using an example.

## Example library

| Product | Version | Reference file | Focus |
| :--- | :---: | :--- | :--- |
| S-HUD | Original | [`S-HUD.lua`](./S-HUD.lua) | HUD exports, notifications and UI interactions |
| S-HUD | v2 | [`S-HUDv2.lua`](./S-HUDv2.lua) | Second-generation HUD integration examples |
| S-Inventory | — | [`S-Inventory.lua`](./S-Inventory.lua) | Inventory integration examples |
| S-Notify | Original | [`S-Notify.lua`](./S-Notify.lua) | Notification integration examples |
| S-Notify | v2 | [`S-Notifyv2.lua`](./S-Notifyv2.lua) | Second-generation notification integration examples |

**Tip:** Open the reference file matching your installed product. Original and v2 integrations should not be assumed to be interchangeable.

## Getting started

1. **Choose your product** from the example library above.
2. **Open its Lua reference file** and review the exports, events and parameter comments.
3. **Copy only the relevant integration calls** into the appropriate part of your own FiveM resource.
4. **Adjust arguments** such as messages, categories and durations to your use case.
5. **Test on your development server** with the matching S-Service resource running.

### Example: S-HUD notification

The original S-HUD reference includes a basic info notification example:

```lua
exports["S-HUD"]:MakeNotifyInfo("info", "S-Service", "Hey, this is a test Notify", 5000)
```

The final argument is the display duration in milliseconds. See [`S-HUD.lua`](./S-HUD.lua) for other interactions, including announcements, help notifications, progress bars and text UI.

## Compatibility and versioning

- Examples are organized by **S-Service product and version**.
- Make sure the corresponding product is present and started on your FiveM server.
- Integration calls may change between product generations.
- These samples provide **usage references**, not guaranteed compatibility with every third-party resource or server setup.

## Support and requests

Need help integrating a product, found an outdated example, or want to request another snippet?

**[Join the S-Service Discord](https://discord.gg/s-service)** and open a support or question ticket. Include the product name, product version, and a brief explanation of what you are trying to achieve.

## Contributing

Contributions and suggestions are welcome. Before proposing a new example:

- Confirm it is relevant to an S-Service product.
- Clearly identify which product version it targets.
- Keep snippets focused and easy to understand.
- Avoid publishing paid or proprietary product source code, secrets, or private configuration.

For suggestions, contact the team on [Discord](https://discord.gg/s-service).

## Links

| Resource | Destination |
| :--- | :--- |
| S-Service Store | [Browse products](https://s-service.tebex.io/) |
| Community & Support | [Join Discord](https://discord.gg/s-service) |
| GitHub Repository | [View source examples](https://github.com/Chrisi816/Code-Beispiele-S-Service) |

---

<div align="center">

**S-SERVICE**

*FiveM resources · Developer integrations · Community support*

Made for developers building with S-Service.

</div>
