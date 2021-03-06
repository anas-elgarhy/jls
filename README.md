# jls: modern ls using java ☕

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=bugs)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=Anas-Elgarhy_jls&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)

![jls](./Screenshots/0.2.2_in_alacritty.png "jls")
![jls -lh](./Screenshots/0.2.2_in_alacritty_with-lh.png "jls -lh")

## Features

- Support text color.
- Support icons for file type (require [nerd-font](https://www.nerdfonts.com)).
- More customization options

## Install

### Linux
- From aur: `yay -S jls`
- Manual:
    - Make sure you installed `wget` and [nerd font](https://www.nerdfonts.com)
    - Run this command
       ```bash
        curl -s https://raw.githubusercontent.com/Anas-Elgarhy/jls/master/scripts/install.sh | sudo bash
       ```

## Uninstall

### Linux
- Manual:
    - Run this command
      ```bash
        curl -s https://raw.githubusercontent.com/Anas-Elgarhy/jls/master/scripts/uninstall.sh | sudo bash
      ```

## Options table

| Option                     | Value                                           | Description                                                     |
|----------------------------|-------------------------------------------------|-----------------------------------------------------------------|
| `--help`                   | n/a                                             | Show help message                                               |
| `-v` or `--version`        | n/a                                             | Show version                                                    |
| `-a` or `--all`            | n/a                                             | Show all files including hidden files                           |
| `-l` or `--long`           | n/a                                             | Show long format                                                |
| `-G` or `--group`          | n/a                                             | Show group name in long format                                  |
| `-h` or `--human-readable` | n/a                                             | Show human readable size                                        |
| `-s` or `--size`           | n/a                                             | Show file size in normal format                                 |
| `-S`                       | n/a                                             | Sort by size (largest first)                                    |
| `-R` or `--revcursive`     | n/a                                             | Show files in sub-directories recursively (not implemented yet) |
| `-ni` or `--no-icons`      | n/a                                             | Don't show icons                                                |
| `-ic` or `--icons-color`   | Icon color in hex format or Auto for auto color | Use custom icons color (not implemented yet)                    |
| `-tc` or `--text-color`    | Text color in hex format or Auto for auto color | Use custom text color (not implemented yet)                     |
| `-no` or `--no-owner`      | n/a                                             | Don't show owner name in long format                            |
| `-nc` or `--no-colors`     | n/a                                             | Don't use colors                                                |
| `-nd` or `--no-date`       | n/a                                             | Don't show last modified date                                   |
| `-nn` or `--no-name`       | n/a                                             | Don't show file name                                            |
| `-L`                       | n/a                                             | Sort by last modified date (latest first)                       |
| `np` or `--no-permissions` | n/a                                             | Don't show permissions in long format                           |
| `-ns` or `--no-size`       | n/a                                             | Don't show the file size                                        |
| `-nt` or `--no-type`       | n/a                                             | Don't show the file type                                        |
| `-c` or `--contents-count` | n/a                                             | Show the number of files in the directory                       |
| `-t` or `--tree`           | n/a                                             | Show the directory tree (not implemented yet)                   |

## Requirements for development:

- [nerd-font](https://www.nerdfonts.com)
- Gradle 7.4
- jdk 17
- IntelliJ IDEA (not required but recommended)

## TODO

- [ ] Add Tests
- [ ] Add Formatter
- [ ] Add configs system
- [x] Crete arch package [created in aur](https://aur.archlinux.org/packages/jls)

### Available in

[![GitHub](https://img.shields.io/badge/GitHub-Main%20repo-brightgreen?style=for-the-badge&logo=GitHub)](https://github.com/Anas-Elgarhy/jls)
[![GitLab](https://img.shields.io/badge/GitLab-Mirror%20repo-brightgreen?style=for-the-badge&logo=GitLab)](https://gitlab.com/java-utils1/jls)
[![BitBucket](https://img.shields.io/badge/BitBucket-Mirror%20repo-brightgreen?style=for-the-badge&logo=BitBucket)](https://bitbucket.org/anas_elgarhy/jls)
[![Codeberg](https://img.shields.io/badge/Codeberg-Mirror%20repo-brightgreen?style=for-the-badge&logo=Codeberg)](https://codeberg.org/java-utils/jls)

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=Anas-Elgarhy_jls)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-black.svg)](https://sonarcloud.io/summary/new_code?id=Anas-Elgarhy_jls)

![License: GPL-3.0](https://img.shields.io/badge/License-GPL%203.0-blue.svg)
