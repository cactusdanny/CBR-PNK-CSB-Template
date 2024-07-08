CBR+PNK CUSTOM SYSTEM BUILD READ ME

Importing this template requires Custom System Builder to be installed on Foundry.

STEP 1: Install "Custom System Builder" and create a game using it as the System.

STEP 2: Copy and paste the whole folder for this project (CBR-PNK-CSB-Template) into whatever folder you have designated for Foundry's User Data.

STEP 3: Login to the game as the Gamemaster.

STEP 4: Go to the "Game Settings" tab and click the "Import templates JSON" button. Select the file "cbr-pnk-CSB.json" from the folder you pasted into your User Data. The game will reload to finish installing the template.

STEP 5: Add the CSS file.

	STEP 5A: by going to the "Game Settings" tab and clicking the "Configure Settings Button". 
 
	STEP 5B: Under the "Custom System Builder" section you will add the path to the CSS file ("cbr-pnk-styles.CSS") under "CSS Style file"
 
	NOTE: This will not show up in Foundry's list of files, even if it's there, nor can it be uploaded through Foundry. It must be added by typing in "CBR-PNK-CSB-Template/cbr-pnk-styles.css" (or whatever your path for it may be, depending on how you organize your User Data folder)

STEP 6: Add in the Fonts. 

	STEP 6A: While in your Custom System Builder game, go to "Game Settings"
 
	STEP 6B: Click the "Configure Settings" button
 
	STEP 6C: Click the "Configure Additional Fonts" button
 
	STEP 6D: Fill in the following fonts one-by-one being sure to hit the "+ Add Font" button after each. They will appear in the list at the top of the Configure Additional Fonts window. Do not deviate from the following structure as it will break the CSS styling. NOTE: All font files can be found in the CBR-PNK-CSB-Template/Fonts folder.

		Font 1: Cygnito Mono
			Font Family: Cygnito Mono
			Font Weight: Regular 400
			Font Style: Normal
			Font File: Cygnito Mono.otf

		Font 2: Monorama
			Font Family: Monorama
			Font Weight: SemiBold 600
			Font Style: Normal
			Font File: Monorama-Medium.ttf

		Font 3: CBR+PNK Icons
			Font Family: cbrpnkicons
			Font Weight: Regular 400
			Font Style: Normal
			Font File: cbrpnk_icons.ttf
