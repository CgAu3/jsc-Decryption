﻿# jsc-Decryption
 
⛔For xxtea only, nothing can be done with bytecode⛔

⚡This is a script that decrypts the coco2d-js.jsc file⚡

🌈The core process is the decryption of **`XXTEA`** and **`GZIP`**.🌈

### Usage :
        python main.py [-d] [xxteaKey] [jscDir]
### Example :
        python main.py -d 6362d9fe-c3ad-47 C:\DecJsc-master\src
### Tips :
        -d or -decrypt [decrypt]
### Outputs :
        The output folder is located in the same directory as the JSC folder.

### ❗Waiting for repair and Known errors :
- [x] The XXTEA&zip mode cannot be decrypted.
- [x] XXTEA mode cannot be decrypted.
- [x] Save and add some undecoded byte files.
![example](https://github.com/Mas0nShi/jsc-Decryption/blob/master/jsc-Decompile_example.png)

If you have any questions, please contact [ MasonShi@88.com ]

# jsc-Encryption
 
### Usage :
        python main.py [-e] [xxteaKey] [outDir]
### Example :
        python main.py -e 6362d9fe-c3ad-47 C:\DecJsc-master\out
### Tips :
        -e [encrypt]
### Outputs :
        The output folder is located in the same directory as the out folder; it is named "enc".

---By Abslb