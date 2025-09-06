# Download and Install Citrix Workspace

* [Installation](#installation)
* [System Requirements](#system-requirements)
* [Configuration](#configuration)
* [Troubleshooting and Support](#troubleshooting)
* [Changelog](#changelog)

## Installation

* Launch the installer and follow the prompts to complete setup.
* Set up the client in line with your organization’s specifications. For detailed steps on installation and configuration, consult the Installation and Setup Guide.

## System Requirements

To ensure a smooth installation and reliable operation, confirm that your system complies with the following prerequisites:

* **Operating System:** Requires Windows 11 24H2 or a newer compatible version.
* **.NET Framework:** Needs .NET Desktop Runtime 8.0 or above.
* **Supported Browsers:** Fully supports modern browsers built on Chromium.
* **Hardware Compatibility:** Optimized for desktops, tablets, and thin clients with processor, memory, and storage that meet Citrix recommendations.

## Configuration

To achieve optimal performance and a uniform user environment, fine-tune the Citrix Workspace App using these configuration options:

* **Beacon Tests:**
  These tests help verify the availability of network routes to Citrix services, ensuring reliable connectivity. Use the Configuration Checker tool to perform these verifications for session stability.

* **USB Device Memory:**
  Simplifies peripheral usage by remembering manually connected USB devices. Once recognized, these devices will auto-connect in future sessions, improving workflow continuity.

* **Store Setup:**
  Admins can assign recognizable store names within the app to aid identification. Options are available to restrict or allow users to modify these names, maintaining consistency across deployments.

* **Power Policy Management:**
  Prevents devices from going into sleep mode during active sessions, helping to avoid disruptions during work.

* **Advanced Customization:**
  Gives IT teams detailed control over visual settings, session preferences, and virtual channel configurations, allowing the environment to be tailored to organizational needs.

For full setup instructions, see the [Citrix Workspace Configuration Guide](https://docs.citrix.com/en-us/citrix-workspace-app/configure-access.html).

## Troubleshooting

The Citrix Workspace App includes a robust toolkit designed to help identify and fix technical issues efficiently. Primary troubleshooting focus areas include:

* **Authentication Issues:**

  * Problems with Single Sign-On (SSO) or Kerberos can typically be resolved by verifying login credentials and Active Directory integration.
  * Repeated login failures may require analysis of authentication logs within the Workspace App.

* **Network Diagnostics:**

  * Use the Connection Strength Indicator for real-time insights into network performance and potential issues.
  * For more in-depth diagnostics, supplement Citrix tools with reliable third-party network analyzers.

* **Device Compatibility Validation:**

  * Ensure USB peripherals, cameras, and audio equipment are supported by your app version. Up-to-date drivers help ensure smooth performance.
  * Citrix documentation contains lists of validated hardware and any known limitations.

* **Log Analysis and Reporting:**

  * Session logs and diagnostics offer critical insights for resolving advanced issues. Admins can use these logs to isolate and address underlying problems more effectively.

* **Session Disconnection Handling:**

  * Analyze client settings, network parameters, and session policies to pinpoint causes of unexpected disconnects.
  * Activating auto-reconnect features can help reduce the impact of short-term network outages.

For comprehensive troubleshooting information, visit the [Citrix Workspace Troubleshooting Page](https://docs.citrix.com/en-us/citrix-workspace-app/troubleshoot.html).

## Changelog

### Version 2409 (Latest)

* **New Enhancements:**

  * Full compatibility with Windows 11 24H2, integrating recent OS improvements.
  * Updates focused on energy efficiency and improved beacon performance.
  * TLS 1.3 enabled by default, delivering enhanced encryption strength.
  * Better virtual desktop handling during resize and launch for a smoother interface.

* **Resolved Issues:**

  * Resolved login issues related to Workspace Environment Management.
  * Addressed display glitches and inaccuracies in resource listings.
  * Fixed problems with USB device disconnections during session restart.
  * Improved error feedback to assist in diagnosing session launch failures.

### Previous Versions

* **Version 2405:**

  * Added Single Sign-On support for ARM64 architecture, expanding supported hardware.
  * Enhanced logging and beacon diagnostics for simplified administration.
  * Improved multimedia performance in Microsoft Teams virtual environments.
  * Introduced MJPEG webcam compatibility for better video quality.
  * Added new customization options for Desktop Viewer, including toolbar and session controls.

* **Version 2403:**

  * Rolled out power-saving options for hybrid deployments.
  * Enhanced domain-based SSO for quicker authentication.
  * Updated to support the latest Chromium Embedded Framework (CEF) releases.
  * Included new security policy features such as process whitelisting and USB control.
  * Simplified installation of the Microsoft Teams VDI plugin for easier collaboration.

## Key Features

Citrix Workspace App for Windows delivers a robust set of capabilities aimed at boosting security, productivity, and usability. Key highlights include:

* **Single Sign-On (SSO):**
  Provides smooth login experiences using domain credentials or Kerberos, ensuring secure and seamless access.

* **Integrated Microsoft Teams Optimization:**
  Enhances the virtual collaboration experience with high-quality audio, video, and advanced Teams-specific features.

* **Streamlined Desktop Experience:**
  Supports fluid desktop launching and resizing, ensuring consistent visual presentation.

* **TLS 1.3 Encryption Support:**
  Implements the most current Transport Layer Security protocol for improved data protection.

* **SOCKS5 Proxy Compatibility:**
  Enables secure and flexible connections across enterprise-level networks.

* **Customizable Toolbar for Desktop Viewer:**
  Allows users to tailor their interface for better accessibility and ease of use.
