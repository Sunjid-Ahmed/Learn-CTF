# LSBlue (516 solves, 220 points)

## Description:
Orca watching is an awesome pastime of mine!

[lsblue.png](lsblue.png)

## Solution:
Given the title of the challenge (LSBlue), we can assume that the flag will be in the LSB blue channel. To extract this, we can try zsteg first as it does this automatically. 

```
pranav@pranav-VirtualBox:~/Desktop$ zsteg lsblue.png 
imagedata           .. text: "Uhv4BR$.<!(2#(0\"(2#*4*4@;L\\l"
b1,b,lsb,xy         .. text: "flag{0rc45_4r3nt_6lu3_s1lly_4895131}"
b2,r,lsb,xy         .. text: "UUTFUUUW"
b2,g,lsb,xy         .. file: PGP Secret Key -
b2,g,msb,xy         .. text: "iiUueUUu"
b2,b,msb,xy         .. text: "TUUUEUTAUE"
b2,bgr,msb,xy       .. text: "VU_UUUUeY"
b4,r,lsb,xy         .. text: "UEUffufffgUfffeeEfUVVuVeUUfVffUUVfvvDffVfUUWeFfVfUfeeUeVffUeWffwffeVffeffVfefffvfUEeffffeUgUUUffVeVeUUVfffUfUfeUWvffVefefUfvfgUUVffgeUvfUUfgffeVeVgfffUUUUUUUUUUUVehveUfUVfegeUUUUVgeUVggeUUUUUUUUUUUeVgvVUUUvUEUVvVuUUUfeUUUVvfVffffVfffeVfgeUUUUUUUVffeUUUUVeV"
b4,r,msb,xy         .. text: "jfnn\"ffjf"
b4,g,lsb,xy         .. text: "\"\"\"\"\"\"\"2"
b4,g,msb,xy         .. text: "DHDDDDDDDL"
b4,b,msb,xy         .. text: "7swwwww73sw337s73swww7swwww7w7773www77sww7swwww7swwwwwwwwswwsw7swwwsw7s7ww77sswwwww7wwwww7sww7333s333swww7333s7s"
```

## Flag:
`flag{0rc45_4r3nt_6lu3_s1lly_4895131}`


