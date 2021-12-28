# SegaDreamcastBiosTextToPTBR
 A Sega Dreamcast BIOS translation to PT-BR fot whose want their emulators or modded consoles to brazilian portuguese.
 This is a binary piece extracted from my original US Sega Dreamcast BIOS. It is basically text, I am pretty sure there is no copyright infringement there.
 In the final version I am thinking only to keep the IPS file as release. Not yet sure how if will turn out to be.

Some things about me and this project:
- I am not a language professional nor a hex hacking expert.
- Sure I am doing this for fun but I guess someone out there can appreciate and point out some flaws on it.
- Safe to tell I am not the kind of person that abandons a project in course, but I am not stupid to insist in something that I am sure fated to fail in the end. If I see something is really bad I can make some drastic decisions.

All that said. I'm glad to do this. Something I've been thinking for long time but I finally have spare time to do so.


Files I am working on for this project:

dc_boot_00034FC0_00035F30.bin
-
The only file I can post here. Consists in a small portion of the original binary file.
Contains all the text in spanish which I already started replacing with brazilian portuguese text.
Starts about the adress 00034FC0 in the original file and ends about 00035F30.
Be careful copying and pasting the text in the binary. If something wrong, the file goes unusable. It MUST be 1x1 to keep the checksum and integrity of the BIOS.

dc_boot.ips
-
IPS patch that can be easily applied with any IPS tool such as Lunar IPS for example.
This way I can totally avoid any legal issues, wich I already think is not a problem but to be completly safe and clean.
Once I finish the first version of this translation this will likely be the only file in the repo.
