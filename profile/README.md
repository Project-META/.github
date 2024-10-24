# META Enhances Tailored Automation (META) [![Sponsor](https://img.shields.io/badge/Sponsor-db61a2)](https://xi-xu.me/#sponsorships)

[![META](https://img.shields.io/badge/META_Enhances_Tailored_Automation-META-000000)](https://github.com/Project-META)

[![Followers](https://img.shields.io/github/followers/Project-META?style=flat)](https://github.com/orgs/Project-META/followers) [![Stars](https://img.shields.io/github/stars/Project-META?style=flat)](https://github.com/Project-META) [![Forks](https://img.shields.io/github/forks/Project-META/META?style=flat)](https://github.com/Project-META/META/forks) [![Watchers](https://img.shields.io/github/watchers/Project-META/META?style=flat)](https://github.com/Project-META/META/watchers)

[![license](https://img.shields.io/github/license/Project-META/META)](https://github.com/Project-META/META/blob/main/LICENSE) [![build](https://img.shields.io/github/actions/workflow/status/Project-META/META/check.yml)](https://github.com/Project-META/META/actions/workflows/check.yml)  [![Telegram Channel](https://img.shields.io/endpoint?label=Channel&style=flat&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2FProject_META&color=blue)](https://t.me/Project_META)

**Original ｜ [Chinese](https://t.me/Project_META/12)**

## Overview

***M***ETA is a JavaScript-based project that simplifies and optimizes the configuration of the ***M***ulti-function network tool — a cross-platform, rule-based utility for managing network and application traffic. It provides extensive support for advanced features and custom configurations.

So, what exactly does the Multi-functional network tool refer to? Well, if you are asking this question, this project may not be for you because you probably don’t need the Multi-function network tool at all.

## Key Features

- **Dynamic Service and Location Management**
  - **Service Configuration**: Easily manage a wide array of services with customizable icons and aliases. Services are defined with a flexible structure that allows for quick updates and additions.
  - **Location-Based Policies**: Implement location-specific rules and icons, supporting a wide range of countries and regions. This feature allows for precise traffic management based on geographic location.
- **Advanced Proxy Group Management**
  - **Custom Proxy Groups**: Create and manage proxy groups with various strategies such as `select`, `url-test`, `fallback`, and `load-balance`. This allows for optimized routing and failover strategies.
  - **Service and Location Proxy Groups**: Automatically generate proxy groups for services and locations, ensuring that traffic is routed through the most appropriate channels.
- **Comprehensive DNS Configuration**
  - **Enhanced DNS Settings**: Supports both Chinese and international nameservers, with options for DNS over HTTPS (DoH) for improved privacy and security.
  - **Fake IP Mode**: Utilize fake IP ranges to enhance privacy and prevent DNS leaks, with customizable filters to exclude specific domains.
- **Robust Rule Management**
  - **Integration with MRS format rulesets**: Seamlessly integrates with our meticulously designed ***[Rulesets in MRS Format](https://github.com/Project-META/rules-mrs)*** and the official MRS format rulesets of the Multi-function network tool. MRS format rulesets are compact and offer more efficient matching, enhancing performance.
  - **Service Rules**: Generate rules for each service to ensure traffic is routed according to predefined policies.
  - **Rule Providers**: Integrate with external rule providers to keep your configuration up-to-date with the latest domain and IP rules.
- **Flexible Configuration Options**
  - **General Configuration**: Set global options such as logging levels, LAN access, and IPv6 support. These settings provide a foundation for customizing the tool to fit specific needs.
  - **TUN and Sniffer Support**: Enable TUN mode for advanced routing capabilities and domain sniffing for enhanced traffic analysis.
- **Error Handling and Validation**
  - **Configuration Validation**: Built-in validation functions ensure that the configuration is correct and complete before applying changes, reducing the risk of errors.
  - **Detailed Error Reporting**: Provides clear and informative error messages to assist in troubleshooting and configuration adjustments.
- **Extensible and Customizable**
  - **Open Source and Community-Driven**: As an open-source project, META encourages community contributions and customization, allowing users to tailor the tool to their specific requirements.
  - **Modular Design**: The codebase is structured to allow easy integration of new features and services, making it adaptable to future needs.

## Demo

***A demo that use META to generate a configuration for the Multi-function network tool is available at 👉 [https://github.com/user-attachments/assets/31b73325-88ee-4d7e-b1b4-17df85e90c09](https://github.com/user-attachments/assets/31b73325-88ee-4d7e-b1b4-17df85e90c09) 👈.***

## Quick Start

Choose one of the following URLs to import the META script:

| Source | URL |
| ------------------------- | --- |
| **GitHub Raw** | [https://raw.githubusercontent.com/Project-META/META/refs/heads/script/META.js](https://raw.githubusercontent.com/Project-META/META/refs/heads/script/META.js) |
| **Xi Xu's Proxy Everything** | [https://proxy.xi-xu.me/?url=https%3A%2F%2Fraw.githubusercontent.com%2FProject-META%2FMETA%2Frefs%2Fheads%2Fscript%2FMETA.js](https://proxy.xi-xu.me/?url=https%3A%2F%2Fraw.githubusercontent.com%2FProject-META%2FMETA%2Frefs%2Fheads%2Fscript%2FMETA.js) |
| **Mirror of Xi Xu's Proxy Everything** | [https://proxy.xixu.us.kg/?url=https%3A%2F%2Fraw.githubusercontent.com%2FProject-META%2FMETA%2Frefs%2Fheads%2Fscript%2FMETA.js](https://proxy.xixu.us.kg/?url=https%3A%2F%2Fraw.githubusercontent.com%2FProject-META%2FMETA%2Frefs%2Fheads%2Fscript%2FMETA.js) |
| **jsDelivr** | [https://cdn.jsdelivr.net/gh/Project-META/META@script/META.js](https://cdn.jsdelivr.net/gh/Project-META/META@script/META.js) |
| **jsDelivr on Cloudflare** | [https://testingcf.jsdelivr.net/gh/Project-META/META@script/META.js](https://testingcf.jsdelivr.net/gh/Project-META/META@script/META.js) |
| **GitHub Proxy** | [https://ghp.ci/https://raw.githubusercontent.com/Project-META/META/refs/heads/script/META.js](https://ghp.ci/https://raw.githubusercontent.com/Project-META/META/refs/heads/script/META.js) |

## Usage Guide

Follow these steps to use META:

### 1. Prepare Base Configuration

Start with a valid configuration file of the Multi-function network tool containing at least one proxy or proxy provider, typically generated by importing a subscription URL into your client.

### 2. Import META Script

- **For M.P.**:
  1. Go to "Override" in the sidebar.
  2. Import the META script via one of the accessible URLs above.
  3. Click the three dots on the script's card, click "Edit File", edit and save the script, if needed.
  
- **For C.V.**:
  1. Navigate to the "Profiles" page.
  2. Visit one of the above URLs, select all, and copy to get the current META script content.
  3. Add META script content to the editor opened by double-clicking the "Global Extend Script" card.
  4. Edit before saving if needed.

### 3. Apply and Update Configuration

- For M.P., click the three dots on the script's card, click "Edit Info", turn on the "Globally Enabled" option, and save.
- For C.V., click "Reactivate Profiles" button in the upper right side of the window.

### 4. Verify the Configuration

Check the client's "Execution Log" or "Script Console" to ensure that the META script executed successfully to generate the new configuration:

- If your base configuration is correct, it will output the number of identified proxies and proxy providers, and the generated configuration in JSON format.
- If there are errors, correct your basic configuration according to the error and the URL in the output.

For other clients, please refer to the official documentation of the corresponding clients.

## Customization Guide

META is highly customizable. Below are some key areas you can modify:

### 1. **Icon Set URL**

Change the `BASE_ICON_SET_URL` or `LOCATION_ICON_SET_URL` constants to use a different icon set.

### 2. **Services**

Modify the `services` array to add or remove services:

- `name`: Service name.
- `icon`: URL of the service icon.
- `alias`: Must be set to the rule set file name when inconsistent with the name.

### 3. **Locations**

Customize the `locations` array to define geographical locations:

- `name`: Location name.
- `icon`: URL of the location icon.
- `filter`: Regex pattern for matching.

### 4. **General Configuration**

Adjust `generalConfig` object, for example:

- `allow-lan`: Set to `true` for LAN access.
- `log-level`: Set logging level (`silent`, `error`, `warning`, `info`, `debug`).
- `ipv6`: Enable/disable IPv6 support.

### 5. **DNS**

Modify the `dns` object to change nameservers and DNS policies.

### 6. **Hosts**

Add custom hosts in the `hosts` object.

### 7. **Domain Sniffing**

Enable and configure domain sniffing in the `sniffer` object.

### 8. **TUN**

Customize TUN settings in the `tun` object.

### 9. **Proxy Groups (be cautious)**

Customize the `proxyGroups` array to set proxy strategy according to actual needs.

### 10. **Routing Rules (be cautious)**

Customize the `rules` array for traffic management.

### 11. **Rule Providers (be cautious)**

Add custom rule providers in the `ruleProviders` object.

It is strongly recommended to refer to the official documentation of the Multi-function network tool when customizing META scripts, especially the areas marked "be cautious".

## Prerequisites

- A valid configuration file with at least one proxy or proxy provider defined.
- A compatible client that supports JavaScript overrides.

## Disclaimer

1. This project is strictly for educational and research purposes.
2. Use at your own risk. The project assumes no responsibility for potential issues.
3. No guarantee of accuracy, completeness, or reliability.
4. Not liable for data loss or damages.
5. Ensure compliance with relevant licenses and legal regulations.
6. No endorsement of third-party hardware/software.
7. User modifications are their own responsibility.
8. Terms may change at any time. By using this project, you agree to these terms.

## License

Copyright &copy; 2024 Project META. All rights reserved.

Licensed under the [GPL-3.0](https://github.com/Project-META/META/blob/main/LICENSE) license.  
