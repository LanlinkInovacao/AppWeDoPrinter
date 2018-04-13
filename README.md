# AppWeDo Printer v1.0.0

AppWeDo Printer is a PDF virtual printer. Check the [releases](https://github.com/LanlinkInovacao/AppWeDoPrinter/releases) page for this project to download a prebuilt MSI package.

## System Requirements

* 64-bit Windows Vista or later
* .NET Framework 4.0 or later

## Building from source

Visual Studio 2017, Wix 3.11, and Votive 2015 are required to build AppWeDo Printer.

AppWeDo Printer links to, and distributes the following third party components:

* Microsoft Postscript Printer Driver (V3)
* Ghostscript (64-bit)
* Redmon 1.9 (64-bit)

## License

Ghostscript and Redmon are distributed under LGPL v3, so AppWeDo Printer is bound by that license.

## Configuration
 
In the application config file (AppWeDoPrinter.exe.config), there are two settings in the "applicationSettings" element:

* ****AskUserForOutputFilename**** - set value to *true* if you want AppWeDo Printer to ask the user where to save the PDF.
* ****OutputFile**** - if there is a constant filename you want the PDF to be saved to, set its value here. Environment variables can be used. AppWeDo Printer will overwrite each time. This setting is ignored if  **AskUserForOutputFilename** is set to *true*. 

