# MacosSymbolicateCrash
Simple symbolicator python script based on 'atos' command

Run sample: 
symbolicate.py {xxx.dSYM/Contents/Resources/DWARF/xxx} {file.diag} {outputFile}

You will need for running this script the following files:

1. Your dSYM file which is created when building in release mode (or if you are intrested in debug as well, use this configuration in Xcode:

![alt text](https://i.stack.imgur.com/MRpbw.png)

2. Your diagnostic/crash report file

3. you can supply output file path, or use the default - /tmp/translatedDiagnostics.log

then, supply the scipts these parameters with the above order. 

