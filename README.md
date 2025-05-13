# Watchlist - List of IP Addresses with Dubious Intentions

## Overview

This repository contains a list of IP addresses identified through failed login attempts on WordPress instances. The data is collected using the WordPress plugin "Limit Login Attempts" and shared in this repository for further use.

## Purpose

The main purpose of this list is for use in:
- Security Information and Event Management (SIEM) systems
- Firewalls and WAFs (Web Application Firewalls)
- Security analysis tools
- Other systems to check for suspicious connections or traffic

## Data Source

The IP addresses in this list were added due to:
- Brute-force attacks on WordPress instances
- Repeated failed login attempts
- Suspicious login patterns

This data is automatically collected by the "Limit Login Attempts" plugin and subsequently transferred to this repository.

## Usage

### Manual Usage

You can download the list and import it into your security system:

```bash
# Clone the repository
git clone https://github.com/wilketob/watchlist.git

# Use the IP list in your system
```

### Automated Updates

You can also set up an automated process to regularly update the list:

```bash
# Clone the repository
git clone https://github.com/wilketob/watchlist.git

# Set up a cron job for regular updates
# 0 */6 * * * cd /path/to/watchlist && git pull
```

## Contributing

If you want to contribute your own suspicious IP addresses:
1. Fork this repository
2. Add your IP addresses
3. Create a pull request

## Disclaimer

This list is provided without any warranty. The accuracy and timeliness of the data may vary. It is your responsibility to verify the IP addresses before taking action.

---

Created and maintained by [Tobias Wilke](https://github.com/wilketob)
