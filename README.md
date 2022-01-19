# MO_dummyArcher

Mortal Online 2 Training Dummy Archer

Archer macro that shoots the Training dummy, equips new arrow stacks and changes bows when durability has run out.

Make sure you start the script with your bow out and 25 arrows equiped

IMPORTANT! Panic button has been added, now you can stop the script anytime by pressing F5 whenever the script is running
## How to use
- You need a Python 3 installed on your device (https://www.python.org/downloads/)
- After python 3 is on your device youll need pyautogui library (https://pyautogui.readthedocs.io/en/latest/) py -m install pyautogui
- After python 3 is on your device youll need pynput library (https://pypi.org/project/pynput/) py -m install pynput
- Then you simply have to open terminal in the folder where the script is located at, have MO2 running and execute the python file, all the instructions and logs will follow in the terminal
- To end the macro press CTRL + C while the terminal in which the script was executed is active. 
- Its adviced to use this script while your game is borderless or windowed

## How it works
Simply shoots the Training dummy with arrows, changes your bow if broken and equips arrows

## How to setup
- Stand in front of Training dummy with your desired weapon in the hand ready to atack
- Have arrow stacks assigned to the hotbar
- Have spare bows assigned in hotbar, if you want to change bows is main one is broken
- self.arrow_keys = ['#', '$', '%', '^', '&', '*', '(', 'ALT+#', 'ALT+$', 'ALT+%', 'ALT+^', 'ALT+&', 'ALT+*', 'ALT+('] #Set the keys under which are arrow stacks mapped
- self.bow_dura = 70 #Set durability of ALL your current and spare bows
- self.spare_bow_key = ['ALT+!', 'ALT+@'] #Set keys under which are your spare bows mappes
- self.draw_bow_key = 'x' # Set key which is used to draw a weapon
- self.sequence_downtime = 5 # Set a time to wait between each attack sequence and equiping arrows sequence