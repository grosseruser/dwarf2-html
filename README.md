# dwarf2-html
Web frontend for the Dwarf II (aka as Dwarf 2 or Dwarf2) Telescope


The Dwarf II telescope is a nice toy with strengths and weaknesses. A weakness is the standard password (DWARF_12345678) for the WIFI without being forced to change it and, much worse, ssh root access with a standard password (rockchip). I can only urge every owner to fix these problems.

Since I was currently on the root shell, I took advantage of the opportunity and created the "www" folder in the "/oem" folder and in it the "index.htm" shared here. This allows the alredy running "nginx" to serve a web interface and uses the Dwarflab API: https://hj433clxpv.feishu.cn/docx/MiRidJmKOobM2SxZRVGcPCVknQg

I haven't yet thought about whether I want to turn this into a project, so I'm just sharing a primitive "proof of concept".

I'm just a little dwarf...

Update 9 Aug 24:
The Dwarf API has been changed and I can't find any documentation at the moment. Unfortunately, I don't have the time to examine the network stream with Wireshark and find out the changes.
The advantage is that you can now access the SD card using a web browser. You can access the contents of the SD card at http://DWARF-IP/sdcard/. If you put the index.html that is in the repository here on the SD card, you can access it at http://DWARF-IP/sdcard/index.htm. Great!

Update 1. Dec 24:
The /oem/www folder no longer serves as a source for the web server. This function is now taken over by the /userdata/www folder, which is reserved for software updates and must not be changed.
Fortunately, a link to API V2 is now available which can be found at https://tinyphoton.feishu.cn/docx/GBkcdldTIo3SrdxFJDscYVYDnvf?fbclid=IwAR0_Vypm8DPk1PPtwllptpWDZmxbCgi3NKVQKV8khDXIvnNay_o67AUgtq4
