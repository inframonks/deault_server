# Ansible Role: CA

[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)

## Description

This role copies the CA certificates to the system trust stores and reloads them.

## Role Variables

The variables that can be overridden are defined in [defaults/main.yml](defaults/main.yml) and [vars](vars) directory. Below are the key variables:

| Name                     | Default Value                | Description                                      |
| ------------------------ | ---------------------------- | ------------------------------------------------ |
| `ca_source_path`         | `../files/ca`                | Path to fileglob ab certs                        |

## Dependencies

None.