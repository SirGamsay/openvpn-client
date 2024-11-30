# openvpn-client
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)
[![License: LGPL-2.1](https://img.shields.io/badge/License-LGPL%202.1-blue.svg)](https://opensource.org/licenses/LGPL-2.1)

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
   ```bash
   git clone https://github.com/SirGamsay/openvpn-client.git
   cd openvpn-client
   ```
3. Install dependencies:
   - [libsecret](https://gitlab.gnome.org/GNOME/libsecret) (LGPL 2.1)
   - [jansson](https://github.com/akheron/jansson) (MIT)
   - [slog](https://github.com/kala13x/slog) (MIT)

4. Build using CMake:
   ```bash
   mkdir build
   cd build
   cmake ..
   make
   ```

## Licenses

This project is licensed under the LGPL-2.1 license. See [LICENSE](LICENSE) for details.

## Dependencies
- **libsecret**: Licensed under LGPL 2.1. See [LICENSES/libsecret-LICENSE](LICENSES/libsecret-LICENSE).
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

Please ensure your code follows the coding style, includes tests (currently we have None), and passes all tests (again, we don't have tests).

## Code of Conduct
By contributing, you agree to follow our Code of Conduct [CODE OF CONDUCT](CODE_OF_CONDUCT.md).

## Disclaimer
This software is provided "as-is" without warranty of any kind. The author is not responsible for any damage caused by the use of this software.
