---
title: A Wii U Common Key Extractor
author.name: GaryOderNichts, Acer_51 (or Arthur)
help-desc: 
aliases: .wiiukey .wiiucommonkey .ckextractor
color: FA0909
---

# This tool is to extract the Common Key from a Wii U's OTP.bin

## Main ways (+downloads)

There are 3 main ways.

**1.** Use [GaryOderNicht's](https://github.com/GaryOderNichts/WiiUCommonKeyExtractor) Common Key Extractor (Windows only) <br> <br>
**2.** Use [Acer_51 (Arthur)'s](https://github.com/acer51-doctom/commonkey_extractor) Common Key Extractor (macOS and Linux) <br> <br>
**3.** Use any Hex editor and on the **OFFSET** 0E0 (or 0xE0), select the first 16 bytes. (No spaces does not count. Yes it's 32 letters and numbers in total.)

## Usage

For GaryOderNicht's one, just execute the file in Releases.

For Acer_51 (Arthur)'s one, in Terminal in the same directory as the file you just downloaded, execute this: <br>`chmod +x commonkey_extractor && ./ commonkey_extractor <path/to/your/otp.bin>` <br> while replacing `<path/to/your/otp.bin>` with the actual path to your OTP.