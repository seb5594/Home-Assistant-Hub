# Home Assistant Hub

[![Home Assistant](https://img.shields.io/static/v1?label=Home%20Assistant&message=Add%20app%20repository&color=18BCF2&style=flat&logo=homeassistant&logoColor=white)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fseb5594%2FHome-Assistant-Apps) [![HACS](https://img.shields.io/static/v1?label=HACS&message=browse%20integrations&color=1877A5&style=flat)](https://github.com/seb5594/Home-Assistant-Integrations)<br>
[![hub sync](https://img.shields.io/github/actions/workflow/status/seb5594/Home-Assistant-Hub/update.yml?branch=main&label=hub%20sync&style=flat)](https://github.com/seb5594/Home-Assistant-Hub/actions/workflows/update.yml) [![apps](https://img.shields.io/static/v1?label=apps&message=2&color=157F71&style=flat)](https://github.com/seb5594/Home-Assistant-Apps) [![integrations](https://img.shields.io/static/v1?label=integrations&message=1&color=157F71&style=flat)](https://github.com/seb5594/Home-Assistant-Integrations) ![repositories](https://img.shields.io/static/v1?label=repositories&message=3&color=5B6770&style=flat)<br>
[![synced](https://img.shields.io/github/last-commit/seb5594/Home-Assistant-Hub?label=synced&style=flat)](https://github.com/seb5594/Home-Assistant-Hub/commits/main)

Everything I publish for Home Assistant in one place: apps for the Supervisor and custom
integrations for HACS. This page is generated from the two catalogs and always shows the versions
they currently pin.

## Get started

| I want to… | Do this |
| --- | --- |
| Install an app | Add the [app catalog](https://github.com/seb5594/Home-Assistant-Apps) with the blue button above, or in **Settings → Apps → App store → ⋮ → Repositories**. Then pick the app in the store. |
| Install an integration | Open the project's repository below and use the *HACS* badge in its README, or add it in **HACS → ⋮ → Custom repositories** with category **Integration**. |
| Report a problem or ask something | Open an issue in the repository of the project concerned. |

## Apps

| App | Version | Architectures | Status |
| --- | --- | --- | --- |
| **[Home Assistant Git Exporter](https://github.com/seb5594/Home-Assistant-git-exporter-Addon)**<br>Export all of your Home Assistant configuration to a git repository of your choice | [![version](https://img.shields.io/static/v1?label=version&message=1.18.1&color=1877A5&style=flat)](https://github.com/seb5594/Home-Assistant-git-exporter-Addon/releases) | armhf · armv7 · aarch64 · amd64 · i386 | [![build](https://img.shields.io/github/actions/workflow/status/seb5594/Home-Assistant-git-exporter-Addon/ci.yml?branch=main&label=build&style=flat)](https://github.com/seb5594/Home-Assistant-git-exporter-Addon/actions/workflows/ci.yml) [![stars](https://img.shields.io/github/stars/seb5594/Home-Assistant-git-exporter-Addon?label=stars&style=flat)](https://github.com/seb5594/Home-Assistant-git-exporter-Addon/stargazers) |
| **[Rsync Local](https://github.com/seb5594/Home-Assistant-Rsync-Local-Addon)**<br>Keep an extra local copy of your Home Assistant files on an attached USB drive. | [![version](https://img.shields.io/static/v1?label=version&message=1.74.3&color=1877A5&style=flat)](https://github.com/seb5594/Home-Assistant-Rsync-Local-Addon/releases) | armhf · armv7 · aarch64 · amd64 · i386 | [![build](https://img.shields.io/github/actions/workflow/status/seb5594/Home-Assistant-Rsync-Local-Addon/ci.yml?branch=main&label=build&style=flat)](https://github.com/seb5594/Home-Assistant-Rsync-Local-Addon/actions/workflows/ci.yml) [![stars](https://img.shields.io/github/stars/seb5594/Home-Assistant-Rsync-Local-Addon?label=stars&style=flat)](https://github.com/seb5594/Home-Assistant-Rsync-Local-Addon/stargazers) |

Apps are built for the architectures listed and run in the Home Assistant Supervisor. Details,
options and documentation are in each app's repository.

## Integrations

| Integration | Version | Home Assistant | Status |
| --- | --- | --- | --- |
| **[PulseAudio Loopback Extended](https://github.com/seb5594/hass-pulseaudio_loopback_extended-integration)**<br>This is a custom component for Home Assistant that extends the original PulseAudio Loopback integration by adding advanced audio routing parameters. | [![version](https://img.shields.io/static/v1?label=version&message=1.0.0&color=1877A5&style=flat)](https://github.com/seb5594/hass-pulseaudio_loopback_extended-integration/releases) | ≥ 2022.4.0 | [![checks](https://img.shields.io/github/actions/workflow/status/seb5594/hass-pulseaudio_loopback_extended-integration/ci.yml?branch=main&label=checks&style=flat)](https://github.com/seb5594/hass-pulseaudio_loopback_extended-integration/actions/workflows/ci.yml) |

Integrations install through HACS and are configured under **Settings → Devices & services**.
Only public projects are listed.

## Say thanks

All my projects are built in my spare time, just for the fun of it. Still, they take a lot of time and care, and many of the smart home gadgets I buy end up here because I want to make them cloud-free and smart-home ready. Every bit of support means a lot to me.

If my work helped you or turned out to be useful, show your appreciation with a hot drink for my next sleepless night.

[![Buy Me a Coffee](https://img.shields.io/static/v1?label=Support&message=Buy%20Me%20a%20Coffee&color=FFDD00&logo=buy-me-a-coffee&logoColor=black&style=for-the-badge)](https://buymeacoffee.com/seb5594) [![PayPal](https://img.shields.io/static/v1?label=Support&message=PayPal&color=0070BA&logo=paypal&logoColor=white&style=for-the-badge)](https://www.paypal.com/donate/?hosted_button_id=QMQPNRENXDN26)

## How this works

Each app or integration lives in its own repository and ships through one shared pipeline. The
[app catalog](https://github.com/seb5594/Home-Assistant-Apps) and the
[integration catalog](https://github.com/seb5594/Home-Assistant-Integrations) pin the latest
version of every public project; this hub reads both and renders the overview every hour and
whenever a catalog changes.
