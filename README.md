# Home-Assistant Snapcast Custom Component

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

> [!CAUTION]
> **Outdated! please use the official add-on!**

This repo contains the snapcast integration and can be added through HACS. My goal is to use this repo for testing and to allow you to use the new features until they get added to the official integration. I plan to add all features to the official integration, but that takes time.

Add to home-assistant:

- HACS: https://hacs.xyz/docs/faq/custom_repositories
- copy the custom_components/snapcast folder in your custom_components folder.

How to help:

- If you discover a bug that exists also in the normal [snapcast integration](https://www.home-assistant.io/integrations/snapcast/), please open an [upstream issue](https://github.com/home-assistant/core/issues)
- If you discover a bug that is related to this version of the snapcast integration please open an issue here
- Pull requests are tricky. If you can, please submit it directly to the home-assistant/core repo. If it depends on changes here, feel free to submit it here, but I will ask you at some point to also submit it upstream. (This might require some rework.)

Status:

- ToDo:
  - Add device information
  - Add option flow, allow to disable groups
  - Add tests
  - Add discovery flow
  - Add change name service
  - Add stream sensor
  - Add capabilities: play/stop/etc, metadata, grouping
- Done:
- Open upstream PRs:
- Merged upstream PRs:
  - Config flow, HA2023.5: https://github.com/home-assistant/core/pull/80288
  - Client/Group state, HA2023.5: https://github.com/home-assistant/core/pull/77449
  - Client/Group names, HA2023.6: https://github.com/home-assistant/core/pull/93116
  - Server updates, HA2023.5.5: https://github.com/home-assistant/core/pull/93010
