# Description
The PPTT or Proteus Penetration Testing Tool is an ID cloner that I have only used for HID iCLASS ID's so far. It has no need for encryption or decryption because it just rips the binary off of an ID and puts it on another
# DISCLAIMER:
Please only use for White Team Application or LEGAL penetration testing
# Usage Guide
To save an ID to emulator memory: "hf iclass esave"  
To save an ID to a .bin file: "hf iclass dump"  
To load an ID to emulator memory: "hf iclass eload -f {file}"  
To use the PPTT to simulate an ID: "hf iclass sim"
To write an ID from emulator memory to ID: "hf iclass restore -f {file} --first 6 --last 18 --ki 0"  
