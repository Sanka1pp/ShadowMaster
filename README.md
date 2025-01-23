# ShadowMaster

**Shadow Master: The Ultimate Bad USB Toolkit for Red Teamers.**

*Plug it in. Extract the secrets. Leave no trace.*

A premier red teaming tool designed to extract valuable information from target systems.

## Introduction

Shadow Master is an advanced red teaming tool that extracts valuable information from target systems, including WiFi passwords, browser saved passwords, and system credentials. It also includes features for persistence mechanisms, privilege escalation, lateral movement capabilities, data exfiltration capabilities, anti-detection and stealth features, comprehensive reporting features, and remote access features.

## Table of Contents

*   [Introduction](#introduction)
*   [Features](#features)
*   [Requirements](#requirements)
*   [Usage](#usage)
*   [Reporting Bugs](#reporting-bugs)

## Features

*   **Advanced Credential Harvesting:** 
    *   Extracts SAM database.
    *   Uses Mimikatz to dump credentials.
    *   Harvests domain controller credentials.
*   **WiFi Password Extraction:** Extracts WiFi passwords from the system.
*   **Browser Saved Passwords Extraction:** Extracts saved passwords from Google Chrome and Mozilla Firefox.
*   **Persistence Mechanisms:** Creates persistence via registry keys.
*   **Privilege Escalation:**
    *   Enumerates vulnerabilities using local exploit suggester tools like Watson or BeRoot.
    *   Automates access token stealing using Incognito or Mimikatz functionalities.
    *   Automates UAC bypasses using tools like UACME or bypassuac.js.
*   **Lateral Movement Capabilities:**
    *   Automated credential replay.
    *   Network share scanning.
    *   Remote desktop session hijacking.
*   **Data Exfiltration Capabilities:**
    *   Compression & encryption of exfiltrated data.
    *   DNS Tunneling as well as other alternative protocols.
*   **Anti-Detection and Stealth Features:**
    *   Signature Obfuscation.
    *   Process Injection.
*   **Comprehensive Reporting Features:** Generates human-readable reports summarizing findings.
*   **Remote Access Features:** Includes Keylogging functionality.

## Requirements

*   Windows operating system (tested on Windows 11)
*   PowerShell version 3 or later

## Usage

Execute the ShadowMaster.duck script on the target system using a USB Rubber Ducky device.

**Please note that you should use this tool for educational purposes only and not for malicious activities.**

## Reporting Bugs

If you find any bugs or issues with Shadow Master, please report them in the Issues section of this repository.

## License

Shadow Master is released under the MIT License.

## Disclaimer

The author of Shadow Master is not responsible for any misuse of this tool. Use at your own risk.
