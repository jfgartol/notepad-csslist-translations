# notepad-csslist-translations
Contribute with the translations to your language of the plugin to edit css files for notepad++

## How to contribute:
Download the empty template cssList.po
### Set language code
Rename to cssList.XX.po, where XX is the code of the language to translate from column the 639-1 in the list of codes from https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes

If your language is french then the name for the po file must be cssList.fr.po, for italian cssList.it.po etc

### Edit content
You can edit the .po file with a text editor or any po editor (https://poedit.net/, https://localise.biz/free/poeditor)
If you prefer edit the file with a plain text editor yo must fill the empty msgstr with the translation of the msgid line

    #: nppforms.rsdirectorynot
    msgid "Directory not found:"
    **msgstr ""**

The text for spanish is as follows:

    #: nppforms.rsdirectorynot
    msgid "Directory not found:"
    **msgstr "No se ha encontrado el directorio:"**
