# PART I- Honing Your C Skills
## CHAPTER I- The C Philosophy
The first C languuage was developed by Dennis Ritchie at Bell Laboratories in 1972 and ran on a DEC PDP-11.
The __ANSI__ standard for C, which replaced the standard writted by _Kernighan and Ritchie_ in 1978.
Here __ANSI__ stands for American National Standard Institute(ANSI). It produces standards that help keep each of the compilers working in the same manner.
#### Power of C
Most of C's power comes from these attributes:
* C can address and manipulate memory by direct address
* C has a powerful library of functions
#### Conditions:
* If the compiler does extend the ANSI compiler minimum limits and you use the extensions, you can be sure that when your program is compiled with another compiler, it will either not compile correctly or not execute correctly.
* Don't use all of the ANSI keywords are in lowercase as identifiers in program.Generally the compilers 'complines' when incorrectly use any reserved keyword.
### A Programming Style
1. Each tab is indented four characters.
2. Lines should be a maximum of 80 characters if at all possible.
3. Comments can use either the __ANSI__ standard /* comment */ or the newer //single line comment.
4. When variables are defined or declared, only one variable is allowed per definition or declaration.
5. All functions are prototyped, either in the header include file, or if there is none at the top of the file.
6. All data objects use Hungarian notation and are mixed case.
7. All function names are mmixed case and should be descriptive of what the function does. If the return is not clear, use Hungarian notation for the function name.
8. Opening and closing braces are on their own lines, aligned in the same column.
9. Comments are just notes to yourself (and perhaps others)remaining you of what you did. 
10. Use blank lines wherever neccessary to make the code readable.
11. Use the variables i,j,k,l,m and n as for() loop indexes, and use them in order._Avoid using these variables for scratch variables._
12. Avoid "cute" code.
13. Use parentheses liberally.
14. Use the new _style_ function headers.
### Hungarian notation:
*_Hungarian notation_ prefixes a variable name with a letter or letters to tell the programmer what data type the variable contains.
*_Hungarian notation_ helps to prevent assigning the wrong data type to a variable, and helps you understand why you are using a particular data object.
### Function declaration:
* When you are writing a function, you must have a function declaration.
__Example1:__
int Myfunction(int n, char a[], char chMode)
__Example2:__
![alt https://in.images.search.yahoo.com/images/view;_ylt=AwrwJTSgf85dan4Ap18O9olQ;_ylu=X3oDMTIzY2ljdWptBHNlYwNzcgRzbGsDaW1nBG9pZAM3YTU3YzgyODlkNGQ3N2U4N2QxODc3MWE5NGQ1N2M0NQRncG9zAzExBGl0A2Jpbmc-?back=https%3A%2F%2Fin.images.search.yahoo.com%2Fyhs%2Fsearch%3Fp%3Dbaby%2Bimages%26ei%3DUTF-8%26fr%3Dyhs-pty-pty_extension%26hsimp%3Dyhs-pty_extension%26hspart%3Dpty%26param1%3D20190316%26param2%3D29c43760-a92f-4b35-b6be-5863073bff6f%26param3%3Dconverter_%257EIN%257Eappfocus1%257E%26param4%3Dd-ccc7-lp0-dsf_converter--bb8%257EChrome%257Ebaby%2Bimages%257EFD23D2B4796C831419B1D60BF87B9B20%26tab%3Dorganic%26ri%3D11&w=1440&h=900&imgurl=wallpapersite.com%2Fimages%2Fwallpapers%2Fstorks-1440x900-baby-hd-4k-animation-2231.jpg&rurl=https%3A%2F%2Fwallpapersite.com%2Fmovies%2Fstorks-baby-hd-4k-animation-2231.html&size=205.9KB&name=Wallpaper+Storks%2C+Baby%2C+HD%2C+4K%2C+Animation%2C+Movies%2C+%232231&p=baby+images&oid=7a57c8289d4d77e87d18771a94d57c45&fr2=&fr=yhs-pty-pty_extension&tt=Wallpaper+Storks%2C+Baby%2C+HD%2C+4K%2C+Animation%2C+Movies%2C+%232231&b=0&ni=288&no=11&ts=&tab=organic&sigr=126dv8rtm&sigb=1ajibhkkl&sigi=12hi5dmqh&sigt=11o2ov6bo&sign=11o2ov6bo&.crumb=ovPs0BKNQmt&fr=yhs-pty-pty_extension&hsimp=yhs-pty_extension&hspart=pty&param1=20190316&param2=29c43760-a92f-4b35-b6be-5863073bff6f&param3=converter_%7EIN%7Eappfocus1%7E&param4=d-ccc7-lp0-dsf_converter--bb8%7EChrome%7Ebaby+images%7EFD23D2B4796C831419B1D60BF87B9B20] (image.jpg)
