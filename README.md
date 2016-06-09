# Office365-XMLGenerator-Utility
This is a PowerShell utility to Dynamically Generate Config.xml File.
Utilty Presents a User Interface to select Optional Office Products and Language Packs to be intalled with office deplployment setup.exe
When the Products and Languages are selected and Button (Generate XML) is clicked then TestConfig.xml is created in         C:\windows\temp directory

LanguageCodes.csv and LanguageCodesHashtable.csv must be kept in root folder as the script is reading values from these files to Design User Interface.

Any chnages in the User Interface can be done through these CSV files. Like adding a New Language or New Products.
