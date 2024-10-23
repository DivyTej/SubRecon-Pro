# SubRecon-Pro
This script is a subdomain discovery and validation tool designed to identify and check the status of subdomains for a given domain. It leverages both active and passive methods to enumerate subdomains, including wordlists, assetfinder, DNS lookups, Google dorks, and subfinder. It can also check if subdomains are alive using HTTP requests and can introduce delays and custom headers to evade detection by security systems.

Key features include:
- Subdomain Enumeration: Utilizes multiple sources (assetfinder, DNS, Google dorks, subfinder) to find subdomains.
- Brute Forcing: Uses a provided wordlist to brute force subdomains if specified.
- HTTP Request Validation: Checks if subdomains are alive by making HTTP requests and examining response status codes (2xx, 3xx, 403, 404).
- Verbose Mode: Provides detailed real-time output if enabled.
- Defense Evasion: With the --bypass-defence flag, it introduces delays, rotates user agents, encode requests and uses custom headers.

This script aims to be a comprehensive tool for security analysts and penetration testers to map out and analyze subdomains while minimizing the risk of detection by security measures.
