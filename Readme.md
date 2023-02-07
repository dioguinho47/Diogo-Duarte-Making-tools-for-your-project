#Module must be launched with Live Server
Based and inspired on the examples given by the teacher, this module was created as a tool that will allow translation between languages in my future application. In this module example, from english-norwegian. 

We have initially created two json files where we will be storing our translations, one for english and another for norwegian. Each translation is given a keyword for example "welcome". In our main file "Translation.mjs" is where we will be applying the functions in order for these translations to work. 

We initially imported our files into our mjs file and gave them unique keywords: "english" and "norwegian". We then in our class create functions for both aquirring the translation that will be used (setTranslation), and then another to retrieve the correct value based on the key in translation. 

The text will be translated with 'translation.setTranslation(norwegian)' where we type in () the keyword given to the imported json files. In this case "norwegian" is for the norwegian translation. In our keys, we wrote "welcome", so it will translate the sentence that is stored with that keyword. 

In order to verify if this test works, we could simply check our console with 'console.log(this.translation[myKey])' and the translation should appear in the console in the language written in translation.setTranslation(). Another example could be an alert, or showing a text on the screen with '.innerHTML'. In addition, we can verify with node by going to our terminal and typing 'node Translation.mjs'. 

