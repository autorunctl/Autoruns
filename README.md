# Autoruns v14.11

Download latest version from Releases:       
https://github.com/appinitx/Autoruns/releases/tag/v14.11

## Introduction

Autoruns is a deep-dive Windows autostart and persistence inspection utility built for responders, malware analysts, and power users who need full visibility into what launches on a system. It enumerates common and obscure execution vectors: Run/RunOnce keys, Startup folders, scheduled tasks, services, drivers, Winlogon and AppInit hooks, shell extensions, browser helper objects, WMI event consumers, image hijacks, and other load points that attackers frequently abuse for stealthy persistence. Compared to basic startup managers, Autoruns correlates entries across user and machine scopes, highlights unsigned or suspicious binaries, and helps you quickly pivot from an entry to its file path, publisher details, hashes, and supporting registry or task metadata.

It’s especially useful for triage: identify unexpected persistence after an incident, validate hardening baselines, or clean up noisy endpoints without reinstalling Windows. Advanced users can filter by signature status, hide Microsoft/Windows components to reduce clutter, and focus on anomalies that matter. Used carefully, Autoruns can also support remediation by disabling or deleting unwanted entries, making it a precise tool for controlling boot-time and logon-time execution surfaces in enterprise and lab environments.
