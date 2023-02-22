## Static Ain't Always Noise

# Solution

After downloading the staic and bash file

rajeev@rajeev-ubuntu:~/Documents/picoctf$ ./ltdis.sh static

  _Attempting disassembly of static ...

  Disassembly successful! Available at: static.ltdis.x86_64.txt

  Ripping strings from binary with file offsets...

  Any strings found in static have been written to static.ltdis.strings.txt with file offset_

rajeev@rajeev-ubuntu:~/Documents/picoctf$ cat static.ltdis.strings.txt 

   1020 **picoCTF{d15a5m_t34s3r_ae0b3ef2}**

