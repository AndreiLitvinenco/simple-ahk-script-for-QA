# AutoHotkey QA Form Pasting Script

### Overview
This AutoHotkey (AHK) script allows you to quickly paste common QA forms such as bug reports, test cases, epics, and stories into various applications or text editors. By assigning hotkeys to specific forms, you can automate the process of filling in repetitive information, saving time and improving efficiency.

### Prerequisites
To use this script, you need to have AutoHotkey installed on your computer. AutoHotkey is a free, open-source scripting language for Windows that allows you to automate tasks and create hotkeys.

You can download AutoHotkey from the official website: [AutoHotkey](https://www.autohotkey.com)

It is known that ahk scripts may trigger false positives by various antiviruses. If this happens to you just ignore it.

You can either use the released version or compile it yourself using the following instructions.

### Manual compile
1. Download and install AHK on your machine if you haven't already.
2. Clone this repo on your local machine.
3. Right click on the script and then click on `compile script`.

### Usage
1. Right click on the `.exe` and then click on `run as administrator`.
2. The script will run in the background and display an AHK icon in the system tray.
3. In order to paste a specific form write the according command.
    * `WRITETEST`   -> for the test case form
    * `WRITEBUG`    -> for the bug report form
    * `WRITEEPIC`   -> for the epic form
    * `WRITESTORY`  -> for the story form
4. Edit the form as you need.
