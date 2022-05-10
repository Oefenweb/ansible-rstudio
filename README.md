## rstudio

[![CI](https://github.com/Oefenweb/ansible-rstudio/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-rstudio/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-rstudio-blue.svg)](https://galaxy.ansible.com/Oefenweb/rstudio/)

Set up (the latest version of) [RStudio (IDE)](https://www.rstudio.com/products/rstudio/download/) in Debian-like systems.

#### Requirements

* `curl` (will be installed)
* `r-base` (will not be installed)

#### Variables

* `rstudio_version` [default: `2022.02.2-485`]: Version to install
* `rstudio_install` [default: `[]`]: Additional packages to install (e.g. `r-base`)

## Dependencies

None

## Recommended

* `ansible-r` ([see](https://github.com/Oefenweb/ansible-r))
* `ansible-rstudio-server` ([see](https://github.com/Oefenweb/ansible-rstudio-server))

#### Example

```yaml
---
- hosts: all
  roles:
    - rstudio
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-rstudio/issues)!
