# Airapport Community Translation
 Text files for Airapport games - make our games playable in your language.

 Airapport games such as [**Farm and Mine**](https://airapport.itch.io/farm-and-mine) and [**Idle Tower Builder**](https://airapport.itch.io/idle-tower-builder) gathered international community: as of Nov 2023 there are over 19000 members on the games' Discord server.

To make it easier for the players who speak different languages to play the games the translation engine is included. Most of the initial trasnlations were made automatically, but many players suggested to help with the texts improvement. 

This repository contains language files which can be edited and placed into the game's data\translations\ folder, and your changes will appear in the game at once. These files are compatible with **Farm and Mine v.1.2.5** or higher and with **Idle Tower Builder v.1.4.11** or higher. 

## How to make fixes in one of the current game languages
This repository contains 2 folders: trans/farm - with the language files for Farm and Mine and trans/tower - with the language files for Idle Tower Builder. These are json files which can be edited with any text editor. The section "phrases" of a language file contains pairs "key":"value" for the translated text. For convenience these pairs are grouped by their meaning: "general interface", "buildings", "inventions", etc. You can corrent any translation or tranlate the terms in "untranslated" groups.

Once done, please, save the file. To test your translation, please, use the Itch version of the corresponding game, and place the updated language file to the data\translations\ folder.

To let other players use your translation, please, update the file in the repository and make a pull request. Don't forget to fill in the "lang_translator" value so that we will thank you in the game!

## How to add new language
Copy en.json file under another name. Fill in the "lang_code" and "lang_selfname" fields to identify new language. Add your information as "lang_translator" and tell about the state of the translation in "lang_translation_comment". And finally, change all the English texts from the keys into the desired language.

Test the translation on your game copy by placing the new file to data\translations\ folder, and once everything is ready, please, submit the new file to this repository to make it available for other players, and to be included into the mobile updates of the Airapport games, too

If your language uses not a latin/cyrillic/vietnamese symbols, please, contact us via general@cardswars.com. We might need to prepare the game engine for new language first.

Thank you for your help!

[Video instruction](https://www.youtube.com/watch?v=uoln-vRKdLc)
