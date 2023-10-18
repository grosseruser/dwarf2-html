# dwarf2-html
Web Frontend for the Dwarf 2 Telescope


The Dwarf II telescope is a nice toy with strengths and weaknesses. A weakness is the standard password (12345678) for the WIFI and, much worse, ssh root access with a standard password (rockchip). I can only urge every owner to fix these problems.

Since I was currently on the root shell, I took advantage of the opportunity and created the "www" folder in the "/oem" folder and in it the "index.htm" shared here. This is run by "nginx" on port 80 as a web interface and uses the Dwarflab API: https://hj433clxpv.feishu.cn/docx/MiRidJmKOobM2SxZRVGcPCVknQg

I haven't yet thought about whether I want to turn this into a project, so I'm just sharing a primitive "proof of concept".

I'm just a little dwarf...
