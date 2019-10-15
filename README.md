# etchGrite
I have to clean up the code and submit JS to a JS file I was having issues with the linking of this and css so I decided to write everything in HTML for now (this also helps me not go from one screen to another/ only having the 16 inch laptop screen to work with can be a pain sometime). 

Currently the game executes as follows
    - Entry street fighter screen is displayed to show nostalgic arcade like street fighter image.
        - start button blinks to draw user attention into button so user is aware they must click the button to continue (this blinking of buttons I use constantly throughout the game to guide the user)
    - Arena screen is dispayed with character selection available, a user can select any character and if the user changes his/her mind the user may select a new character and this new one will be shown. Once user is satisfied witht the character they must confimr their hero. 
    - After hero is selected the remaining characters (only character missing from selection screen will be the hero selected by the user) will move to the right hand side for an enemy to be selected. The user once again has the ability to change his/her mind about which character to select. Once the enemy the user wants is selected the user must confirm the enemy by cicking on the "enemy confirmation" button. 
    - Now that we have a hero and enemy selected we can begin attacking (the attack button will show after enemy confirmation is clicked on). The heros attack will gradually increase while the enemy attack remains the same throughout the battle. A healthpoint health bar as well as text is clearly displayed above the hero and enemys character. If the hero losses the user is alerted a loss statement. If the hero wins the user can now select the next enemy (enemies who have been defeated already will not be displayed for selectiong).

Eventually when I have some more free time I want this game to have the following properties and be able to share with prospective employers. 
    - Hero (user character): 
        - will have 4 different attacks (each with different strength) that can be used only a set amount of times. 
        - when using each attack the hero will animate said attack visual (hopefully i can find gifs that cover this)
    - Enemy (computer character)
      - will have 4 different attacks (each with different strength) that can be used only a set amount of times.
      - when using each attack the hero will animate said attack visual (hopefully i can find gifs that cover this)
      - the computer will randomly select wich attacks to execute
    - I also want to add some more audio
        - When a character is attacked a grunt audio is played
        - win("WINNER!" in video game voice)/loss("KO" in video game voice) audios 
    - Possible arena selection screen to be made available after the character selection is completed. 
