# QR code generator using Python
This script take a link of any URL and generate a `QR code` corresponding to it.
### Prerequisites
`Python 3`
### Library Used
* [qrcode](https://github.com/lincolnloop/python-qrcode)

### To install required external modules
Run `pip install qrcode` 

### How to run the script
- Provide your desired URL in the script
- Execute `python3 QR_code_generator.py`
### Program:
```
import qrcode

data = """Product: Toor dal
Weight: 1 kg
MRP: Rs.100
Packing Date: 15-01-2024"""

qr = qrcode.make(data)

qr.save("toor_dal_qr.png")

print("QR Code generated and saved as 'toor_dal_qr.png'")
```
### Screenshot showing the sample use of the script
<img width="450" height="450" alt="toor_dal_qr" src="https://github.com/user-attachments/assets/ea382342-f290-4bc7-875d-e01239cb303a" />


## *Author Name*
B Harshala Reddy
