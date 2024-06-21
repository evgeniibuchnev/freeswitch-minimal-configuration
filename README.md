# Minimal FreeSWITCH Configuration

This repository contains a minimal FreeSWITCH configuration aimed at providing a foundational setup for those who are new to FreeSWITCH or need a streamlined configuration for testing and development purposes. The goal of this configuration is to demonstrate the basic functionalities of FreeSWITCH with minimal complexity, allowing users to get started quickly and easily.

## Features

- **Basic SIP Profiles**: Pre-configured SIP profiles for simple SIP endpoint registration and communication.
- **Dialplan Examples**: Basic dialplan configurations to handle inbound and outbound calls.
- **Default Extensions**: Sample extensions to demonstrate internal calling capabilities.
- **Minimal Modules**: Only essential FreeSWITCH modules enabled to keep the configuration lightweight and straightforward.
- **Configuration Templates**: Template files provided to simplify customization and extension of the configuration.

## Getting Started

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/evgeniibuchnev/minimal-freeswitch-configuration.git
    cd minimal-freeswitch-configuration
    ```

2. **Install FreeSWITCH**: Follow the [official FreeSWITCH installation guide](https://freeswitch.org/confluence/display/FREESWITCH/Installation) for your operating system.

3. **Apply Configuration**:
    - Backup any existing FreeSWITCH configuration files and remove everything from FreeSWITCH configuration directory.
    - Copy the files from this repository into your FreeSWITCH configuration directory (typically `/usr/local/freeswitch/conf` or `/etc/freeswitch/`).

4. **Start FreeSWITCH**:
    ```sh
    freeswitch -nc
    ```

5. **Register a SIP Client**:
    - Use the provided SIP profiles and extensions to register a SIP client (softphone or hardware phone).
    - Make and receive test calls to verify the configuration.

## Contributing

We welcome contributions to enhance this minimal configuration. If you have improvements or additional minimal features that align with the goals of this repository, please submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This minimal configuration is intended for educational and development use. For production environments, it is recommended to review and customize the configuration according to specific needs and security requirements.
