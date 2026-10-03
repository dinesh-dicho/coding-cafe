
1) pwd means print working directory. Executing it printed the current path where we are working. In my case it is /Users/dineshchoudhary.

2) ls -a also displayed a few files and folder differentiated by a . or .. in front of them. These are likely hidden files and folders that are not visible directly. ls means list.

3) ls -l displayed a bunch of lines. The first line says "total 0" which means total files in the current directory are zero. The first column in one of the line says drwxr-xr-x which is different from others by a lot since it differntiates from others due to being a user generated folder (created by me).

4) After creating the README.md, from where I stand ,i.e in the coding-cafe directory, the command doesnt work. Since with respect to the current directory the command is not accurately relative path. With respect to the root directory, the command would be a relative path.

5) mv did two different jobs. The first was to move the file README-backup.md from the coding-cafe directory to the week01 folder. Also in the next line mv renamed the file to old-readme.md.

6) 13 folders are there on my PATH.

7) The address is /opt/anaconda3/bin/python3

8) No they are not the same. I am on macOS while the person next to me is on windows. Regardless it will be different as each device has different folders.

9) It said zsh: command not found: pyton3 when I ran it directly. This means that the entered command is incorrect. On running it as 'which pyton3',the error was 'pyton3 not founc' which means that in my PATH there is no such file or directory.

10) .venv did not appear in ls because it likely is a hidden file which only showed itself after entering ls -a.

11) At the beginning of every prompt, (.venv) now appears.

12) The path shown now says /Users/dineshchoudhary/coding-cafe/.venv/bin/python3 . The path is not the same anymore. It might be because activate moved the python3 file into location that the source command specified 

13) The first list only stated the package pip and its version 26.1.2, but the second list also showed packages named certifi, charset-normalizer,idna,requests,urllib3 with their versions.

14) After using deactivate command to exit the virtual environment, python3 points back to it's old path now.

15) On executing it, it tells ls to follow the flags specified. In case the flags are not -f,-d,-l then it assumes this option by default.

16) Using ctrl+c copied my terminal window and ctrl+d printed/created a new terminal inside the window containing the same contents (and all of them run the same commands?).

# Finished early part (XD)-
1) It displays the size in the appropriate units which is good in general?
2) Absolutely nothing. The only taks it performs is to take us back to the root directory from current location.
 
 Will finish remaining later...