# PDUEncoder: A Python Class for PDU Encoding

## Overview
`PDUEncoder` is a Python class designed for encoding strings into the PDU (Protocol Data Unit) format. It offers functionality to convert strings into their PDU representation, mainly used in SMS (Short Message Service) and telecommunications. The class handles various character encodings and provides methods for binary and hexadecimal conversions.

## Features
- **Seven-Bit Default Alphabet**: Supports a wide range of characters in the seven-bit default alphabet used in SMS.
- **Binary and Hexadecimal Conversions**: Includes methods for converting binary strings to integers, integers to hexadecimal strings, and vice versa.
- **String to PDU Conversion**: Converts any given string into its PDU representation.

## Installation
No special installation is required. You can include this class directly into your Python project. Ensure you have Python installed on your system.

## Usage
To use the `PDUEncoder`, simply import the class into your Python script and create an instance of it. Here's a basic example:

```python
from pduencoder import PDUEncoder

# Create an instance of PDUEncoder
encoder = PDUEncoder()

# Example string
input_string = "Hello World"

# Convert the string to PDU format
pdu_string = encoder.string_to_pdu(input_string)

print(f"PDU Format: {pdu_string}")
```

## Contributions

Contributions and suggestions are welcome! Feel free to fork the repository, create issues, or submit pull requests.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code in accordance with the license terms.
