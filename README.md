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
5. Update AppIcons.js file
const icons = {
    explore: [20],
    home: [20],
    me: [20],
    notifications: [20],
    challenges: [20],
    <ADD NEW TAG NAME>
};
6. Rename file from selection.json to icomoon.json and copy to the folder
Styles > icons > icomoon.json

and run:

react-native link

Reference links
https://medium.com/bam-tech/add-custom-icons-to-your-react-native-application-f039c244386c
https://www.reactnative.guide/12-svg-icons-using-react-native-vector-icons/12.1-creating-custom-iconset.html
