Vicidial Webphone - Lightweight Agent Interface (VLA)
This project provides a lightweight webphone interface for Vicidial agents, built on WebRTC technology. VLA aims to offer a user-friendly and efficient experience for managing calls directly from a web browser.

Inspired by CyburPhone (https://github.com/carpenox/CyburPhone)

Features:

WebRTC integration: Utilizes WebRTC for real-time communication, eliminating the need for plugins.
Browser compatibility: Designed to work with modern web browsers like Chrome, Firefox, and Edge.
Vicidial integration: Seamless integration with Vicidial server, leveraging existing functionalities.
Basic call management: Initiate calls, answer incoming calls, and hang up calls directly from the web interface.
Lightweight design: Offers a clean and focused interface for improved agent productivity.
Installation:

Prerequisites:

Vicidial server (version needs to be specified based on compatibility)
Asterisk PBX with WebRTC support
Steps:


Follow the detailed configuration guide provided within the repository to configure:
Asterisk (specifically chan_webrtc.conf and sip.conf)
Apache (virtual host configuration for the webphone)
Vicidial (settings adjustments within the admin panel)
Firewall (opening ports for WebRTC communication)
Build and Run:

Instructions for building and running the webphone application will be provided in the project's documentation.
Usage:

Once configured, agents can access the webphone interface through a designated URL provided by your Vicidial administrator. The interface will allow them to manage inbound and outbound calls, enhancing their workflow within the Vicidial environment.

Contributing:

We welcome contributions to improve this project. Please refer to the CONTRIBUTING.md file for guidelines on submitting bug reports, feature requests, or code contributions.

License:

This project is licensed under the MIT License (refer to LICENSE.md for details).

Disclaimer:

This project is provided for educational and demonstration purposes. While we strive for functionality and stability, limited support is available. Use at your own discretion.

For ViciDial Installation and Support visit https://absolute-global.com