# textTOspeech
this is ezra talking this project was about the sign language interpreter system

#import the pakage named as "pyttsx3" which will provide all the needed functions
import pyttsx3

#this line will initiates pyttsx3 
text_s = pyttsx3.init()

#code will take the input data from user
input_data = input("provide your input text :- ")

#text to speech the given text and this will translate text user provides
text_s.say(input_data)

#lastlly it will runs 
text_s.runAndWait()

"""some point may be usefull some system will be need pyttsx3 upgraded version so they can litrarry has to install pyttsx3 allong with
pip3 install pyttsx3 type this command on your system 
