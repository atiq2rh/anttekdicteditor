AntTekDict Editor is a simple tool to convert dictionary data in  StarDict’s format (both 2.4 and 3.0) to AntTekDict’s format.

# Requirements #
Java Runtime Environment JRE 1.5+ (download and install  from Oracle site http://www.oracle.com/technetwork/java/javase/downloads/jdk-6u26-download-400750.html)

# Download #
[AntTek Dict Editor](http://anttekdicteditor.googlecode.com/files/AntTekDictEditor.jar)

# Convert StarDict data to AntTekDict data #
After installing JRE and downloading AntTekDict Editor, click on AntTekDictEditor.jar to launch the editor. Suppose that you have already StarDict data, the following steps detail how to convert into AntTekDict data. ![http://anttek.com/wp-content/uploads/2011/07/AntTekDict_Editor1.png](http://anttek.com/wp-content/uploads/2011/07/AntTekDict_Editor1.png)

  1. Select input: click Browse to select the folder, which contains the original dictionary data (StarDict 2.4 or StarDict 3.0). ![http://anttek.com/wp-content/uploads/2011/07/input.png](http://anttek.com/wp-content/uploads/2011/07/input.png)
  1. Select output: select the folder, which contains the data after conversion. ![http://anttek.com/wp-content/uploads/2011/07/output.png](http://anttek.com/wp-content/uploads/2011/07/output.png)
  1. Select other settings according to your original data including data type (database or StarDict), source language, target language, type formater, …
    * Data Type: the return data format, we supported: Database, Index (StarDict 3.0 data type), IDX (StarDict 2.4data type). Especially at the IDX format, the input data must is StarDict 2.4. Note, you should choose the output format as database because it makes query faster and also avoids “out of memory” error.
    * SourceLanguage: the source language of the dictionary.
    * TargetLanguage: the target language of the dictionary.
    * Formatter: the type formatter for the dictionary, this option supports to display the content,which returned by a query data.
    * Morpho: morphology for dictionaries, support for the original investigation. Currently, we only support this function for the English, French, German.
    * Has Accent: support functions from the unsigned check: true if the language input has accent (ex: Vietnamese, French …), false if the language input is unsigned type (ex: English, Chinese …).
    * Encoding: setting charset. The default is utf-8.
  1. Click on the button “Builder” to convert
  1. Copy the output folder into $SD\_CARD$/AntTekDict/data folder
  1. Open AntTekDict application, press menu/Reload to update dictionary list