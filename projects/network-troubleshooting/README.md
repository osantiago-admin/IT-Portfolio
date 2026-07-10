# 🌐 Network Troubleshooting Lab

## Overview

This project documents my process for diagnosing and resolving common network connectivity issues in an IT support environment. The goal was to simulate a real-world help desk scenario by identifying the root cause, using diagnostic tools, and documenting the resolution process.

---

## Scenario

**User Issue:**

A user reports they are unable to access company resources and are experiencing intermittent network connectivity issues.

**Environment:**

- Windows workstation
- Corporate network environment
- TCP/IP networking
- DNS and DHCP services

---

## Objectives

- Troubleshoot network connectivity problems
- Identify common causes of network failures
- Use command-line diagnostic tools
- Analyze IP configuration and network communication
- Document troubleshooting steps and resolutions

---

## Troubleshooting Process

### 1. Gather Information

- Asked the user questions to identify symptoms
- Determined whether the issue affected one user or multiple users
- Verified error messages and affected applications
- Identified when the issue started

---

### 2. Physical & Hardware Checks

- Confirmed network cable connections
- Verified device power status
- Checked network adapter status
- Confirmed network interface was enabled

---

### 3. Diagnostic Commands Used

### `ipconfig`

Used to verify:

- IP address configuration
- Default gateway
- DNS settings
- DHCP information

### `ping`

Used to:

- Test network connectivity
- Verify communication between devices
- Identify possible connection failures

### `tracert`

Used to:

- Analyze network paths
- Identify possible routing issues

### `nslookup`

Used to:

- Verify DNS resolution
- Confirm hostname-to-IP address mapping

---

## Example Resolution

**Issue:**

User could not access network resources.

**Root Cause:**

Incorrect IP configuration preventing proper network communication.

**Resolution:**

- Renewed IP address configuration
- Verified DNS settings
- Tested connectivity using diagnostic commands
- Confirmed successful network access was restored

---

## Tools Used

- Windows Command Prompt
- Windows Network Settings
- PowerShell
- ipconfig
- ping
- tracert
- nslookup

---

## Skills Demonstrated

- Network troubleshooting
- TCP/IP fundamentals
- DNS troubleshooting
- DHCP troubleshooting
- Connectivity testing
- User support
- Technical documentation

---

## Screenshots

*(Screenshots of troubleshooting commands and results will be added here.)*
