# AdaFormat
This is a frontend for the program reformat which will reformat and syntax colour Ada source code.
The output is either text or RTF depending on what features are selected (syntax colouring => rtf).
The command line program 'reformat' was NOT written by me and has its own documentation in the !Reformat.Docs directory.
                                    
# Frontend use
 
1. Run !AdaFormat. This will place an icon on the iconbar icon.
2. Click SELECT on the !AdaFormat iconbar icon. This will open the setup
   window.
3. Drag the file you want to reformat / syntax colour to the
   'Sourcefile' icon. This will insert the path of the dragged file.
4. Click SELECT on the 'Run' icon.
5. A window will open which will display any message from the command
   line program (error messages).
6. When the command line program has completed the job another window
   will open (a SaveAs window) from which you drag the resulting file to
   a filer display in order to save it.
   
You can skip 1. & 2. by dragging the source file directly on top of the 
AdaFormat iconbar icon.

You can skip 5. by selecting the 'AutoSave' entry in the AdaFormat iconbar 
'Options' menu. This will save the file in the same directory as the
source file and with 'RFRM_'+<sourcefilename> as name.

## Setup window

   Icon  |            Action/Meaning         |              Default
   ----   |           --------------          |             -------
   Sourcefile|        This is the path of the source file (mandatory, typed or dragged) |    nil
                     

## Setup Menu

   Entry |                  Action/Meaning              |         Default
   -----  |                 --------------               |        -------
   Command line |         Any other options can be entered.(See the manual for full details.)     | auto
                           

## Display (AdaFormat) Window

This window is opened automatically and displays messages produced by the reformat command line program (error messages).
   
## Display (AdaFormat) Menu:
From this menu you can pause/continue and abort the reformat command line program.

