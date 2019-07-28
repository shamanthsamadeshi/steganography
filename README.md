
# Simple STEGANOGRAPHY tool.

##Author : Shamanth Samadeshi

##Github : https://github.com/shamanthsamadeshi


##HELP :

 --carrier    : Give path of carrier file which will contain our text
 --stego_text : Enter text to hide
 --stego_find : Give path of image which contains hidden text


##REQUIREMENTS :
 
 pip install steganography 


##USAGE : 

#Hide

 python stego.py --carrier --stego_text "Enter Text"

#Retrive 

 python stego.py --stego_find "image_name.jpg/jpeg/png" 