# iconsfont
This repository contains embeddable icons font for Mobile 3.0

1. Go to https://icomoon.io/app/#/select/font

2. Add fonts and download file


3. Add the font to your project 
CustomFontApp/
  android/
  ios/
  assets/
    fonts/

4. Link your font
	"rnpm": {
		"assets": [
			"assets/fonts/icon"
		]
	}

5. Rename file from selection.json to icomoon.json and copy to the folder 
Styles > icons > icomoon.json

and run:

react-native link



