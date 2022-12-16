# tripleDESanyfile

Aim to develop a DES based encryption method to encrypt any kind of file.
AND ALSO CONVERTING TO STANDALONE SINGLE APPLICATION FOR WINDOWS, LINUX, MAC OS SEPERATELY.

IMPLEMENTED ON PYTHON 3.9.2
Libraries: -
getpass (inbuilt python 3.9.2)
pycrypto (2.6.1)
(Make sure you install and build all the depedencies required by above libraries)

Can encrypt any kind of file like:

    *Text  File
    *Image File
    *Video File
    *Docx  File 
    *Exe   File
Capability: - Max 500 MB file on At least 2GB RAM Processor i3 Or avove


FEATURES:

Password hashing - PBKDF2 used(I will welcome advanced modes)
Salting done
Hashing and salting password performed multiple times (>10,000)
Peppering not done as it increases load in server, faster method are welcome
Digital signature in form of SHA256 used
Documentation provided in code
CBC (Cipher block chaining used) - Triple DES
Initialization vector for CBC is derived from the password hash itself.
Tested on Linux and Windows based systems.