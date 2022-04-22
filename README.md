# ALE: ACT Log Extractor

ALE is an open-source tool that reads a Final Fantasy XIV [ACT (Advanced Combat Tracker)](https://advancedcombattracker.com/) `.log` file and extracts text from player chat channels without any of the jargon.

![image](https://user-images.githubusercontent.com/63081353/164064994-43c64442-6124-4a45-9e2e-1ef24f411251.png)

* ### **It is highly recommended that the user create backups of their original ACT log files before performing any operation on them, out of an abundance of caution.**

* **ACT logs do not record [Auto-Translate words](https://ffxiv.fandom.com/wiki/Auto-translator).** However, everything else in the message is still recorded in the ACT log.

* **ACT must be running in order for ACT to create logs.** If ACT is not running during a chat, the chat log **will not be recorded**.

* **ALE does not create ACT logs.** ALE only parses ACT logs. ALE also does not parse the game's own log files at this time.

* Screenshots, video recording, and manually copying chat logs in-game are all alternative options to use in addition to ALE for backing up chat logs.

## Usage

1. Check or uncheck which channels to include or exclude.

2. Check or uncheck whether to include channel labels, timestamps, and message spaces.

3. Optionally add or remove name filters by entering a name in the text box and either pressing `Enter` or clicking the `+`, and selecting a name in the list box and pressing `Delete` or clicking the minus `-` button.
   * Only messages from characters with the inputted names will be extracted.
   * You can add or remove character names to the Saved Names list. These names will persist even when the program is closed and reopened. 
   * You can transfer names from the Saved Names list to the Name Filters list by selecting a name and then pressing the single arrow `>` button, or hitting the `→` key. 
   * You can transfer all of your Saved Names to the Name Filters list by pressing the double arrow `>>` button.
   * You can transfer names in the Name Filters list to your Saved Names list by hitting the `←` key.

2. Click on the `Select File and Extract` button.

3. Navigate to and select the log file(s) to extract from.
    * ACT log files are usually found in `AppData\Roaming\Advanced Combat Tracker\FFXIVLogs`.

4. Wait for the log file to be parsed.
    * ACT log files can be very large, so this may take some time. 

5. Click OK on the confirmation window.

6. Select the save destination for the parsed output. 
    * The default filename is `ExtractedLog.txt` and will save in the same directory as ALE by default. The user may enter a different filename or use a different file extension if they wish. 
    * The newly saved file will automatically open in the user's default program for the filetype after saving.
    * There is also a button in ALE to conveniently open ALE's directory.


## Contact

Discord: yesokcool#8548
