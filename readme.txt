*************** Naming Standards (abbreviatoins and ambiguouty are not allowed) ***************

Files/Folders (ie. index.html project-data.json)
- File names are lowercase letters

-Folders names are UpperCamelCase

- spaces are represented as hypens.

HTML
- 

CSS Variables (https://en.bem.info/methodology/naming-convention/)
- Names are written in lowercase Latin letters.

- Words are separated by a hyphen (-).

- The block name defines the namespace for its elements and modifiers.

- The element name is separated from the block name by a double underscore (__).

- The modifier name is separated from the block or element name by a single underscore (_).

- The modifier value is separated from the modifier name by a single underscore (_).

- For boolean modifiers, the value is not included in the name 



CSS Classes (https://en.bem.info/methodology/naming-convention/)
- Names are written in lowercase Latin letters.

- Words are separated by a hyphen (-).

- The block name defines the namespace for its elements and modifiers.

- The element name is separated from the block name by a double underscore (__).

- The modifier name is separated from the block or element name by a single underscore (_).

- The modifier value is separated from the modifier name by a single underscore (_).

- For boolean modifiers, the value is not included in the name 

CSS Animations (https://en.bem.info/methodology/naming-convention/)
- Names are written in lowercase Latin letters.

- Words are separated by a hyphen (-).

- The block name defines the namespace for its elements and modifiers.

- The element name is separated from the block name by a double underscore (__).

- The modifier name is separated from the block or element name by a single underscore (_).

- The modifier value is separated from the modifier name by a single underscore (_).

- For boolean modifiers, the value is not included in the name 

JS Functions (https://google.github.io/styleguide/jsguide.html#naming-rules-common-to-all-identifiers)
- lowerCamelCase

JS Constants (https://google.github.io/styleguide/jsguide.html#naming-rules-common-to-all-identifiers)
- CONSTANT_CASE

JS Classes (https://google.github.io/styleguide/jsguide.html#naming-rules-common-to-all-identifiers)
- UpperCamelCase and for methods within the class lowerCamelCase

JSON (https://google.github.io/styleguide/jsoncstyleguide.xml?showone=Property_Name_Format#Property_Name_Format)
- Property names should be meaningful names with defined semantics.

- Property names must be camel-cased, ascii strings.

- The first character must be a letter, an underscore (_) or a dollar sign ($).

- Subsequent characters can be a letter, a digit, an underscore, or a dollar sign.

- Reserved JavaScript keywords should be avoided (A list of reserved JavaScript keywords can be found below).

********************************************************************************************************************

*************** Animations Guide (this is for JavaScript) ***************
- Animations shall be exported frame by frame as webp  (do not get rid of duplicate frames).

- The names of the exported frames shall be the frame # only (etc 12.webp).

- The folder containing exported frames shall be named what the animation is named. 

- Folder Names shall be UpperCamelCase and contain no special characters (HighFivingSomone).

- Animations are assumed to be run at 24 frames per second

- The JSON file containing the information for animations shall have the duration, name/file location. 
********************************************************************************************************************

*************** JSON Data  ***************
- Do not store any personal or confidential information within the JSON file as it will be available publicly.

- projectdata.json contains information about the projects (description, timeline, skills, etc)

- Organize projectdata.json from most important project to least important project.

- 

- Organize employerdata.json by both most important and most recent.


********************************************************************************************************************
