patchrom_nypone_kernel
======================
- To make you just need to run:<br>
$ ./makee <br>
<br>
then you need to implent cert file into boot.img by doing this => <br>
1 - Open both your kernel and cert file with your favorite HEX editor, <br>
2 - Copy all of the cert file hex <br>
3 - Replace all copied HEX into 0X00000094 to 0X000004E5 <br>
4 - Change 0X2C from 03 to 04 <br>
That is all ;-)
