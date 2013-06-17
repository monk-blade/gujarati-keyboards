gujarati-keyboards
==================

Customized Keyboards for Gujarati language with IBus 

Supported Operating Systems : Debian,Ubuntu,Fedora,Arch Linux and other linux distributions

Supported Fonts : Aakar,Padmaa,Samyak,Raghu,Rekha,Lohit Gujarati and Other Gujarati Unicode fonts.

Current Status : Beta 

###Dependencies
Please install m17n package using following command.

> sudo apt-get install m17n

(Above command is for Ubuntu and other Debian based operating system)

###Installation
Download above mim files and place those .mim  files at /usr/share/m17n/.

###Usage
Set default keyboard layout as IBus and Add your own keyboard in IBus preferences.

###Whats new
- Latest Feature :
 - Defualt itrans method requires a vowel at the end of each word, otherwise the last letter of the word will be a half letter. When you become expert in typing, it is very very distressing that you have to type "a" to complete the last letter. For example, if you want to type "ભારત", you have to type "bhaarata". (Note the last "a".) I made your life much easier than you think. If you press space bar at the end of the word, that word will automatically become complete, so you have to just type "bharat" and then press space bar and it will complete the last letter. so you will be able to type with your fullest speed. 
- (Itrans and Phonetic both) Rupee symbol instead of dollar key.
- Following error solved in default itrans keyboard.
 - If you type "છે." in default itrans method it will type "છe."
 - Some default key modification 
