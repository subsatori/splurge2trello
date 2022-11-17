
# splurge2trello

## Description
This signed Apple iOS shortcut applies to producers wanting to upload audio files to their Magic Music Machine style Trello board.

## Functions
- Takes the shared audio from your app as input and re-encodes as AAC 256 kbps. Your original export isn’t saved.
- Sets the meta-data of this file to your chosen artist name (choose once at import), Album name is set to “Splurges [year]”
- Removes a specific unneccessary string with date and time from the export out of audio app Auxy from the end of the name to use in the next step. The audio file name remains unchanged.
- Creates a new Trello Card with the cleaned name as the Card’s Name, sets “due date” to 3 days and attaches the converted audio file. The card is put at the bottom of your chosen splurge List in your chosen Board.

## Setup

* Import to Shortcuts and answer the import questions with your preferences.
* Once imported, press and hold down on the "…"-button in the "splurge2trello" shortcut area.
* Select details
* Enable "Show in Share Sheet" and press Finish

## Usage

* Export your audio from your music app. If you have quality options lossless is preferred as audio will be re-encoded.
* Find splurge2trello in the share sheet  
* In the integrity dialog about creating Trello cards, choose to always allow. This needs to be done once per app export: 

At Trello a new card with the audio as attachment and a name based on the file name will have been created. If not, which does happen but shouldn't happen often, it commonly is sufficient to repeat once.

For more usage details concerning Shortcuts see The Shortcut manual: 
https://support.apple.com/guide/shortcuts/ (Select your iOS version)

## Compatibility

Likely at least iOS 12 and later.

## Input
If you have suggestions for other regexes for file names from your audio app, get in touch.


