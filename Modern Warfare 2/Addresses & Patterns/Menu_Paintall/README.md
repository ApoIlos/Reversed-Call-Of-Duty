## How to find
* Step 1: Load the game in ida(x32 bit)
* Step 2: Press Shit & F12 to grab strings
* Step 3: Look for "fps: %f\n%.0f, %.0f" With out "". Image > https://prnt.sc/x42b9h
* Step 4: Then click on the sub on the right(It won't be named Menu_PaintAll). Image > https://prnt.sc/x42dzf
* Step 5: Once you are there rename the sub so you remember what it is. Image > https://prnt.sc/x42j4e
* Step 6: You can make a sig using the SigMaker plugin or copy the bytes(See my tut on showing bytes) Image > https://prnt.sc/x42nu7
* Step 6 Info: Use the sig as a update helper not for hooking.

## Address
* 1.2.211: 0x005A8770

## Pattern
* IDA Style: A1 ? ? ? ? 80 78 0C 00 0F 84 ? ? ? ? 53 56 
* Code Style: \xA1\x00\x00\x00\x00\x80\x78\x0C\x00\x0F\x84\x00\x00\x00\x00\x53\x56, x????xxxxxx????xx
