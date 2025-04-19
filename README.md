# PassChecker - Password Analyzer
PassChecker is a web tool that allows you to analyze password security quickly and easily, available at [https://dddevid.github.io/PassChecker/](https://dddevid.github.io/PassChecker/).

## Features

- **Complete analysis**: Evaluates password strength based on entropy, length, and character variety
- **Cracking time estimation**: Calculates the time needed to force the password with different types of hardware
- **Dictionary check**: Checks for common words in Italian and English
- **Data breach verification**: Checks if the password has been exposed in known data breaches
- **Personalized suggestions**: Specific advice to improve password security
- **Light/dark theme**: Interface adaptable to user preferences
- **Responsive design**: Works on desktop and mobile devices
- **Privacy-first**: No data is sent to external servers (except for anonymized data breach checks)

## How It Works

PassChecker evaluates password security by analyzing:

1. **Length**: The longer the password, the more secure it is
2. **Complexity**: Use of uppercase, lowercase, numbers, and special characters
3. **Entropy**: Mathematical measure of password randomness
4. **Known vulnerabilities**: Check for common words and data breaches

## Technologies Used

- HTML5
- CSS3 with animations and dark/light theme
- Pure JavaScript (Vanilla JS)
- Font Awesome for icons
- Public APIs for data breach verification

## Local Installation

To run PassChecker locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/dddevid/PassChecker.git
   ```

2. Open the `index.html` file in your preferred browser.

No additional dependencies or configurations required.

## Privacy

PassChecker runs entirely in the user's browser. The only exception is the data breach verification, which uses a proxy service to anonymously query LeakCheck.net's public API.

**Important note**: Passwords entered are never stored or sent to our servers. The data breach check happens through a CORS proxy that hides the user's IP address.

## Contributing

Feel free to contribute to the project by opening issues or sending pull requests. Any feedback is welcome!

1. Fork the repository
2. Create a branch for your changes (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add a new feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is distributed under the MIT license - see the LICENSE file for details.

---

Created with ❤️ by [dddevid](https://github.com/dddevid)
