# string_to_pdu_converter
GSM Modem PDU Converter: A Python module for converting USSD codes, such as '*544#', to GSM 7-bit packed format, specifically tailored for compatibility with older Huawei modems like E160. Inspired by http://smstools3.kekekasvi.com/topic.php?id=288

## Features

- **USSD Code Conversion:** Easily convert USSD codes to GSM 7-bit packed format.
- **Huawei Modem Compatibility:** Optimized for seamless integration with older Huawei modems, including the E160 model.

## Manual Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/PinchPitar/string_to_pdu_converter.git
   cd string-to-pdu-converter

## Example Usage

1. **import the file**
    ```python
      from string-to-pdu-converter import PDUConverter
    
      # Create an instance of the PDUConverter class
      new = PDUConverter()
    
      # Use the string_to_pdu method
      input_string = "*544#"
      pdu_result = new.string_to_pdu(input_string)
    
      # Print the result
      print("PDU Result:", pdu_result)


## Contributions

Contributions and suggestions are welcome! Feel free to fork the repository, create issues, or submit pull requests.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code in accordance with the license terms.
