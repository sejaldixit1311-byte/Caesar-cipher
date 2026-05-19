## Caesar Cipher ##
classical encryption . python. beginner project
input : "hello world" -> shift +3 -> "khoor zruog"
input : "khoor zruog" -> shift -3 -> "hello world"

## Overview ##
A command-line implementation of the classical Caesar Cipher encryption algorithm. The program allows users to encode or decode any message by shifting each letter a specified number of positions through the alphabet. Non-alphabetic characters such as spaces and punctuation are preserved as-is.
## Features ##
- Encode
- Decode
- Loop Mode
- Safe Input
## How it works ##
User Input -> Check Direction -> Apply Shift -> Wrap (mod 26) -> Output
## Getting started ## 
1. clone the repo
   -git clone https://github.com/sejaldixit1311-byte/Caesar-cipher.git
   -cd caesar-cipher
2. run the program
   - python caesar.py
3. follow the prompts
  # Example session
    -type 'encode' to encrypt, type 'decode' to decrypt:
    -encode
    -Type your message:
    -hello world
    -Type the shift number:
    -5
    -Here is the encoded result: mjqqt btwqi 

# project structure 
 - ## caesar.py ##  Main program file containing the cipher logic and user interaction loop
    

