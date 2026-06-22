# PiWall

![alt text](PiWall.png)

## What is PiWall?

PiWall is an open-source project that uses a Raspberry Pi 5 (16GB RAM) to act as a firewall. PiWall includes several features:

- **Web Dashboard** — A full web dashboard for configuring everything on the go, hosted directly on the Raspberry Pi for 24/7 access.
- **Traffic Filtering** — A C++ engine for filtering traffic, blocking ports, and more.
- **AI Features** — A local AI model hosted on the Raspberry Pi that can configure settings and provide advice.

## Why use PiWall?

PiWall is designed to be easier to set up than something like PfSense, requiring much less technical know-how especially with the built-in AI assistant to help configure things.

## Features

### General
- **Firewall Enabled** — Toggle the core firewall on/off.
- **Monitor Traffic Enabled** — Enable real-time traffic monitoring.
- **Device Monitor Enabled** — Track devices connected to the network.
- **Malicious Monitor Enabled** — Flag and monitor suspicious/malicious activity.
- **AI Enabled** — Turn on the local AI assistant for configuration and advice.
- **Extensions Enabled** — Enable support for add-on extensions/plugins.

### Privacy & Security
- **Child Filter** — Content filtering for child safety.
- **Yubikey Verification** — Hardware key (Yubikey) authentication for dashboard access.
- **Auth Password Enabled** — Require a password for dashboard/settings access.

### Webhooks
- **Discord Webhook Enabled** — Send alerts and notifications to a Discord channel.
- **Twilio Webhook Enabled** — Send SMS/call alerts via Twilio.
- **AI Webhook Enabled** — Trigger AI-driven actions or notifications via webhook.
- **Get Webhook Enabled** — Allow external GET requests to retrieve PiWall data.
- **Post Webhook Enabled** — Allow external POST requests to push data/events into PiWall.