# OBSCURO 

![ObscuroLogo](https://raw.githubusercontent.com/dogaegeozden/obscuro/main/obscuro.jpg)

Obscuro is a command line tool to encrypt or decrypt files. It encrypts files by rewriting their binary code. 

## INSTALLATION 
1) ```curl -L https://github.com/dogaegeozden/obscuro/releases/download/encryption/obscuro.deb -o obscuro.deb```
2) ```sudo dpkg -i obscuro.deb```

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
