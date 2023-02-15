# OBSCURO 

![ObscuroLogo](https://cdn.pixabay.com/photo/2017/07/26/11/47/magic-2541458_960_720.jpg)

Obscuro is a command line tool to encrypt or decrypt files or folder. You can also encrypt or decrypt folders recursively by using the "-r" option. Otherwise, subdirectories will be skipped and only the files in the target folder will be encrypted.

## INSTALLATION 
1) ```pip3 install cryptography```
2) ```git clone https://github.com/dogaegeozden/obscuro.git```
3) ```cd obscuro```
4) ```sudo dpkg -i obscuro.deb```

## OPTIONS
    -e, --encrypt 
        Use this option to encrypt a particular file or all the files in the target directory. Subdirectories are skipped.

    -d, --decrypt
        Use this option to decrypt a particular file or all the files in the target directory. Subdirectories are skipped.

    -r, --recursive
        Use this option to encrypt or decrypt files recursively.

## EXAMPLES
    obscuro -e <target_path>
    obscuro -d <key_path> <target_path>
    obscuro -r -e <target_path>
    obscuro -d -r <key_path> <target_path>
