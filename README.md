# Semicolon-Checker-in-ImageJ-Macro-Scripts

# ImageJ Macro Syntax Checker
## A Python script that checks for missing semicolons in ImageJ macros.

### Requirements
Python 3.x
re module (included in Python standard library)

### Usage
- Clone the repository or download the 'ImageJ_Semicolon_check_Macro_scripts.py' script.
- Open a command prompt or terminal and navigate to the directory containing the syntax_checker.py script.
- Run the script by typing 'ImageJ_Semicolon_check_Macro_scripts.py', followed by the path to your ImageJ macro file. For example:

ImageJ_Semicolon_check_Macro_scripts.py C:\path\to\your\macro.ijm

- The script will scan the macro file for missing semicolons and print the line number and contents of each line with missing semicolons.
- If no semicolons are missing, the script will output "No ';' is missing.".

### Notes
- The script only checks for missing semicolons at the end of lines. It does not check for other syntax errors in the macro file.
- The script does not modify the macro file in any way.
- The script ignores lines that start with // or /*.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements
This script was created by Nuno Machado.
