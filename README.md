# Develop By Guuu9

## LIST
**Web Projet**
 - [PacketChecker](https://guuu9.github.io/packet_Checker/)
   
***



### PROJECT Packetchecker
Check Receive Packet To Protocol.

[Open PacketChecker](https://guuu9.github.io/packet_Checker/)

Development Tool : Android Studio  
Language : Flutter 3.27.4/Dart 3.6.2  


|OS|           Run Test            |
|:---|:-----------------------------:|
|Android|               X               |
|iOS|               X               |
|WEB| File Load ERR / USE DROP FILE |
|Windows|               O               |
|macOS|               O               |
|LINUX|               X               |

**How To Use Packet Checker**
1. Create `protocol.csv`

    EX) example.csv
    |NAME|BYTES|
    |:---|---:|
    |START|1|
    |DATA 1|10|
    |DATA 2|7|
    |DATA 3|3|
    |END|1|
2. Drag & Drop `protocol.csv` File To Packet Checker Page
3. If you need XorCheck, Insert Hex value in `Exception Hex` & Calculate Hex value in `Decoding Hex` like `0xFF` or `FF`
4. Write Receive Packet In `insert PACKET HEX`
5. CheckBox is `Use / unUse` Option. unUse Option will dismiss

**USE Develop Package & Assets**  
- Package
    - [GETX](https://pub.dev/packages/get)
    - [File_Picker](https://pub.dev/packages/file_picker)
    - [cp949_codec](https://pub.dev/packages/cp949_codec)
    - [csv](https://pub.dev/packages/csv)
    - [desktop_window](https://pub.dev/packages/desktop_window)
    - [desktop_drop](https://pub.dev/packages/desktop_drop)

- Assets 
    - [D2Coding Font](https://github.com/naver/d2codingfont)

> File Drop & File Picker Reference
    https://cyj893.github.io/flutter/Flutter12/


