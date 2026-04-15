# PureVPN Account Checker

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Python](https://img.shields.io/badge/python-3.7+-green)
![License](https://img.shields.io/badge/license-MIT-red)

**Advanced PureVPN Account Checker with Plan Detection**

</div>

## 📋 Features

- ✅ **Multi-Threaded Checking** - Fast account verification with configurable threads
- 🔍 **Plan Detection** - Automatically detects VPN plan type (Standard, Plus, Max)
- 📅 **Expiration Detection** - Identifies expired subscriptions
- 🆓 **Free Account Detection** - Detects free tier accounts
- 🔑 **2FA Detection** - Detects accounts with two-factor authentication
- 🚀 **Proxy Support** - HTTP/HTTPS proxy support with rotation
- 📁 **File Dialog Integration** - GUI file selection for combo and proxy files
- 📊 **Automatic Result Sorting** - Saves results to separate files based on status
- 🎨 **Colored Console Output** - Easy to read, color-coded results

## 🎮 What It Does

This tool checks PureVPN accounts and determines their subscription status. It can identify:

- **HIT** - Active paid subscriptions with plan details
- **FREE** - Free tier accounts
- **EXPIRED** - Expired subscriptions
- **2FA** - Accounts with two-factor authentication enabled
- **BAD** - Invalid or incorrect credentials

## 📁 Output Files

| File | Description |
|------|-------------|
| `hits.txt` | Active paid accounts |
| `free.txt` | Free tier accounts |
| `2fa.txt` | Accounts with 2FA enabled |
| `expired.txt` | Expired subscriptions |
| `capture.txt` | Detailed logs with VPN credentials |

### Output Format


