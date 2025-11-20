# Fail2Ban Rules for Joomla!-Login

## Overview

Use these Fail2Ban rules to block IP addresses after multiple invalid login attempts.

## Customizing

Customize "logpath" in jail.d/joomla-login-errors.conf to suit your needs

## Example Log-Output
```
tail -f /var/log/fail2ban.log |grep joomla
2025-11-19 18:14:35,410 fail2ban.filter [...]: INFO [joomla-login-errors] Found xx.xx.xx.xx - 2025-11-19 18:14:35
```