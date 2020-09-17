# PDF - Char Counter

## About
This is a simple bash script for Mac OS that allows you to check how many
characters are present in a PDF document.

## Installation
To install this program, just run the following command in the terminal
```bash
sudo wget -O /usr/local/bin/pdf_char_counter
http://github.com/karma-riuk/pdf-char-counter && echo "Install successful" ||
echo "Something went wrong"
```
And insert your password after running the command.

If the line "Install successful" appears as the last line of output, the
program is installed! If you didn't see that and you instead saw "Something
went wrong", please read next section.

### Failed Install
In case the install command listed above had "Something went wrong" as last
line, then the alternative install would be to run these commands:
```bash
cd `mktemp -d`
git clone https://github.com/karma-riuk/pdf-char-counter
sudo install pdf-char-counter /usr/local/bin/pdf-char-counter
```

## Usage
To use this program, simply create a symbolic link in the directory where are
located the PDF files that you want to count characters. After the link was
made, simply double-click the link and a terminal will pop-up. In this
terminal will be displayed every PDF file located in directory where the link
is together with it's character count.

Example:
```
Something.pdf: 93482 characters
somthing_else.pdf: 589393949 characters
```

## Contact
If ever you encounter problems during the install or the usage of this
program, please feel free not to contact me, ever. I'm a programmer, not a
personal assistant.