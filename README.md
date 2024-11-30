# openvpn-client

OpenVPN-Client is a simple terminal interface for managing multiple OpenVPN sessions. It supports:
- Starting and stopping OpenVPN sessions.
- Storing passwords securely in GNOME Keyring using the libsecret library.
- Executing custom bash scripts upon connection establishment and termination.

## Features
- Multi-session management.
- Password storage via GNOME Keyring.
- Custom connect and disconnect bash scripts.

## Installation

1. Clone this repository:
   git clone https://github.com/SirGamsay/openvpn-client.git
   cd openvpn-client

2. Install dependencies:
   - libsecret (LGPL 2.1)
   - jansson (MIT)
   - slog (MIT)

3. Build using CMake:
   mkdir build
   cd build
   cmake ..
   make

## Dependencies
- **libsecret**: Licensed under LGPL 2.1. See [LICENSES/libsecret-LICENSE](LICENSES/libsecret-LICENSE).
- **jansson**: Licensed under MIT. See [LICENSES/jansson-LICENSE](LICENSES/jansson-LICENSE).
- **slog**: Licensed under MIT. See [LICENSES/slog-LICENSE](LICENSES/slog-LICENSE).

## Licenses

This project is licensed under the LGPL-2.1 license. See [LICENSE](LICENSE) for details.

### Dependency Licenses
- **libsecret**: Licensed under LGPL-2.1. See [LICENSES/libsecret-LICENSE](LICENSES/libsecret-LICENSE).
- **jansson**: Licensed under MIT. See [LICENSES/jansson-LICENSE](LICENSES/jansson-LICENSE).
- **slog**: Licensed under MIT. See [LICENSES/slog-LICENSE](LICENSES/slog-LICENSE).

## Contributing
Feel free to fork the repository and submit pull requests. If you have suggestions or issues, open a GitHub issue.

### How to Contribute
1. Fork the repository.
2. Create a feature branch (`git switch -c feature-name`).
3. Commit your changes (`git commit -am 'Add feature'`).
4. Push the branch (`git push origin feature-name`).
5. Create a new Pull Request.

Please ensure your code follows the coding style, includes tests (currently we have None), and passes all tests.

## Code of Conduct
By contributing, you agree to follow our Code of Conduct (coming soon).

## Disclaimer
This software is provided "as-is" without warranty of any kind. The author is not responsible for any damage caused by the use of this software.
