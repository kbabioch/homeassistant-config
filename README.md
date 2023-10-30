# HOME ASSISTANT CONFIGURATION

This repository contains my Home Assistant configuration files and serves multiple purposes, i.e. is a backup for me, template for others.
As such it forces me to keep the configuration files clean.

Home Assistant has partly moved away from YAML-based configuration files that are managed manually in favor of UI-based workflows (see [this blog post for details][ha-blog-yaml-future], which means that not everything can easily be stored and shared in a public Git repository.
Nonetheless, I'm trying to configure as much as possible by directly editing the YAML-based configuration files and versioning them here in this repository.

The configuration is heavily based upon [configuration packages][ha-doc-configuration-packages] to organize the configuration files.
The configuration files are split into multiple files, typically one file for each device with multiple domains (e.g. `sensors`, `binary_sensor`, etc.), as this seems to be the most logical way, in particular when dealing with KNX-based devices.

This repository essentially the current state of my (main) Home Assistant instance.
As such it is work-in-progress and might change, whenever I see the need for it and/or find time for it ;-).

I'm providing this to the public as is.
Feel free to use this (partly) as is, and raise issues in case of questions and/or feedback.
I'm also happy to learn new things about Home Assistant (and in general), so also let me know if you see potential to substantially improve the structure and configuration details.

[ha-blog-yaml-future]: https://www.home-assistant.io/blog/2020/04/14/the-future-of-yaml/
[ha-doc-configuration-packages]: https://www.home-assistant.io/docs/configuration/packages/
