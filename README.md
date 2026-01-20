# my_personal_whitelist

A simple repository to store a whitelist of domains that need to be accessible for various applications and services.

## Usage

The `whitelist.txt` file contains domains (one per line) that should be whitelisted in your network configuration, firewall, or proxy settings.

### Format

- One domain per line
- Lines starting with `#` are comments
- Wildcards are supported (e.g., `*.example.com`)

### Example Domains Included

- **VSCode**: Domains required for Visual Studio Code to function properly, including updates, marketplace access, and telemetry

## How to Use

1. Review the domains in `whitelist.txt`
2. Configure your firewall, proxy, or network settings to allow access to these domains
3. Add or remove domains as needed for your specific requirements

## Contributing

Feel free to add domains that you find necessary for your workflows.