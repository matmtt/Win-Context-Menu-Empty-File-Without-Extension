# Windows Context Menu - Empty File Without Extension

The main motivation behind this was to save some clicks, as Windows prompts a confirmation dialog every time you try to change a file’s extension (e.g., when starting with an empty .txt file that you want to rename and change the extension).

After checking some on-line solutions to create a registry entry for a Empty File without any extension in windows, none of them really worked.
Then I got the idea to trying to to create a registry entry that would run a CMD command to create the file. 

## Images

Add 'Create Empty File' option to Windows Explorer context menu:

![image](https://github.com/user-attachments/assets/b1d8d6d4-baa6-4163-b8c8-55dfdc1c3c49)

By clicking it, a new file without extension is created:

![image](https://github.com/user-attachments/assets/70d44e6d-4024-4678-bd88-486188a62a6b)

## How to install
Download the registry entry AddEmptyFile.reg here: https://github.com/matmtt/Win-Context-Menu-Empty-File-Without-Extension/blob/main/AddEmptyFile.Reg 
After installing it, right click on the desired location and create the empty files.
