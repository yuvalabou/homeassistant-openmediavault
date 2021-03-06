{% if installed %}
{% if version_installed.replace("v", "").replace(".","") | int < 110  %}
**IMPORTANT: Integration needs to be re-added after update.**
{% endif %}
{% endif %}

![OpenMediaVault Logo](https://raw.githubusercontent.com/tomaae/homeassistant-openmediavault/master/docs/assets/images/ui/header.png)

Monitor your OpenMediaVault 5 NAS from Home Assistant.

Features:
* Filesystem usage sensors
* System sensors (CPU, Memory, Uptime)
* System status sensors (Available updates, Required reboot and Dirty config)
* Disk and smart sensors

## Links
- [Documentation](https://github.com/tomaae/homeassistant-openmediavault/tree/master)
- [Configuration](https://github.com/tomaae/homeassistant-openmediavault/tree/master#setup-integration)
- [Report a Bug](https://github.com/tomaae/homeassistant-openmediavault/issues/new?labels=bug&template=bug_report.md&title=%5BBug%5D)
- [Suggest an idea](https://github.com/tomaae/homeassistant-openmediavault/issues/new?labels=enhancement&template=feature_request.md&title=%5BFeature%5D)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/G2G71MKZG)
