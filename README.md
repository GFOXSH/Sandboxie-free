# Sandboxie-free
The project was created in response to an attempt by the Sandboxie-plus developer to hide part of the program code.

The goal of the project is to unlock all the features of Sandboxie-plus with minimal changes. Since it is impossible to recompile the project in its original form, the changes will be made at a low level assembler.

To ensure correct operation, before the first launch, you must enter the following commands on the cmd running as administrator:
```
bcdedit.exe -set loadoptions DISABLE_INTEGRITY_CHECKS
bcdedit.exe -set TESTSIGNING ON
```
Then reboot your computer.

Currently only 64-bit version is supported.