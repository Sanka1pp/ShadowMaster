           
# ShadowMaster 
**ShadowMaster: Unleash the Ghost in the Machine**
Created by Sanka1pp 

*Plug it in. Extract the secrets. Vanish.*

A discreet and potent toolkit for red teaming engagements, designed to infiltrate target systems with surgical precision.

## Introduction

ShadowMaster is a stealthy and versatile red teaming tool that silently extracts critical information from compromised systems. From harvesting sensitive credentials and WiFi passwords to establishing persistent backdoors and executing privilege escalations, ShadowMaster empowers operators to maintain covert access and achieve their objectives with minimal risk of detection. 

## Table of Contents

*   [Introduction](#introduction)
*   [Features](#features)
*   [Requirements](#requirements)
*   [Usage](#usage)
*   [Reporting Bugs](#reporting-bugs)

## Features

*   **Advanced Credential Harvesting** 
      *   Extract sensitive credentials from the SAM database.
      *   Employ Mimikatz for advanced credential dumping techniques.
      *   Harvest high-value targets, including domain controller credentials.
*   **WiFi Password Extraction** 
      *   Ghostly acquisition of WiFi passwords stored on the target system.
*   **Browser Saved Passwords Extraction** 
      *   Discreetly extract saved passwords from popular browsers like Chrome and Firefox.
*   **Persistence Mechanisms** 
      *   Establish covert persistence on the target system through carefully crafted registry entries.
*   **Privilege Escalation** 
      *   Leverage local exploit suggester tools like Watson or BeRoot to identify and exploit vulnerabilities.
      *   Automate access token stealing with Incognito or Mimikatz for seamless privilege escalation.
      *   Execute UAC bypasses with tools like UACME or bypassuac.js for elevated privileges.
*   **Lateral Movement Capabilities** 
      *   Automate credential replay for seamless lateral movement across the target network.
      *   Conduct stealthy network share scanning to identify valuable targets.
      *   Hijack remote desktop sessions for discreet access and control.
*   **Data Exfiltration Capabilities** 
      *   Exfiltrate sensitive data with discretion using compression and encryption techniques.
      *   Utilize covert channels like DNS tunneling for stealthy data exfiltration.
*   **Anti-Detection and Stealth Features** 
      *   Employ advanced signature obfuscation techniques to evade detection by security systems.
      *   Leverage process injection techniques for increased stealth and persistence.
*   **Comprehensive Reporting Features** 
      *   Generate detailed and human-readable reports summarizing findings for analysis and future operations.
*   **Remote Access Features** 
      *   Maintain covert access with keylogging functionality for continuous intelligence gathering.

## Requirements

*   Windows operating system (tested on Windows 11)
*   PowerShell version 3 or later

## Usage

1. **Prepare for Operation:** Load the ShadowMaster payload onto a USB Rubber Ducky or compatible HID device using the provided DuckyScript.
2. **Ghostly Insertion:** Discreetly insert the USB device into the target system.
3. **Execute the Mission:** ShadowMaster will autonomously execute the payload, silently gather intelligence, and store the results.
4. **Retrieve the Spoils:** Extract the harvested data, including WiFi passwords, browser credentials, system reconnaissance, and more, from pre-formatted text files.

**Disclaimer:** This tool is intended for legitimate red teaming and penetration testing activities only. Any unauthorized use is strictly prohibited.

## Reporting Bugs

If you encounter any issues or bugs, please report them in the Issues section of this repository.

## License

ShadowMaster is released under the MIT License.

## Disclaimer

The author of ShadowMaster is not responsible for any misuse of this tool. Use at your own risk. 

