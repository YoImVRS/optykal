# optykal v0.0.1

This is a testing script that allows you to make requests to URLs for ethical and legal purposes. You can use it to evaluate the availability and performance of a website, as well as perform load testing.

## Requirements

- Node.js (version 8 or higher)
- npm (Node.js package manager)

## Installation

1. Clone the repository or download the script files to your local machine.
2. Open a terminal and navigate to the location of the script.
3. Run the following command to install the dependencies:

   ```shell
   npm install
   ```
   
## Usage

The script uses the `axios` library to make HTTP requests. Before running the script, make sure you have a file named `agents.optykal` in the script's directory. This file should contain a list of User-Agent strings to be used in the requests. Each User-Agent should be on a separate line.

Once you have prepared the `agents.optykal` file, you can run the script using the following command:

```shell
node index.js --target <URL> --time <seconds>
```
Replace <URL> with the target URL to which you want to send the requests. Replace <seconds> with the number of seconds for which the requests will be sent.

## Example

   Suppose you want to test the URL https://www.example.com for 60 seconds. The command to run would be:
   
   ```shell
   node index.js --target https://www.example.com --time 60
   ```
   
   ![image](https://github.com/ottersek/optykal/assets/121310374/18d532d0-e20a-42aa-a959-926d55fd07cd)

   
## License

This script is distributed under the MIT License. Before using it, make sure to read and understand the terms of the MIT License. You can find a copy of the license in the `LICENSE` file in this repository.

Please note that this script is provided as is, without any warranties or conditions. The use of this script is solely at the user's own risk. No liability is accepted for any inappropriate or unlawful use of the script.

## Contributions

This script is open source, and contributions from the community are appreciated. If you use this script in your project, it is appreciated to acknowledge its origin and the individuals who have contributed to it. However, specific copyright statements are not required, as it is distributed under the MIT License.

Enjoy using this optykal URL testing script!

---

*Note: This script is provided for educational and testing purposes only. Make sure to use it in accordance with the applicable laws and regulations in your jurisdiction. The use of this script for illegal or malicious activities is not recommended or endorsed.*
