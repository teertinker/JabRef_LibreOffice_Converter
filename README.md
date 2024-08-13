# JabRef_LibreOffice_Converter
A LibreOffice extension that converts JabRef references to plain text code and vice versa so that you can use your references with MS Office and other software.

Currently the newer version seems to be broken, I advice to use the old version.

HowTo
=====
- Donwload & install the extension in LibreOffice (**JabRefConverter.oxt**)
- Restart Libreoffice
- Open your manuscript
- Click on the JabRef icon
- Convert


What it does
============
- Convert references created by JabRef into plain text code with a certain pattern: \cite{_1_Bibtexkey}
  - now you can use every text processor
- Convert the text pattern to a JabRef reference
  - you can create a proper reference list regardless which word processor was used before
- **Special feature:** 
  - You can add references by using the \cite{key} function of JabRef (Press: CTRL+K in JabRef). 
  - It will be converted to a proper citation
  - This way you can work with your manuscript even without a connection to LibreOffice.
  
  
Pictures
============
 
A manuscript:  
<img width=“300” src="Readme_images/Bildschirmfoto vom 2020-10-16 20-32-00.png"> 

Convert to text code:
<img width=“300” src="Readme_images/Bildschirmfoto vom 2020-10-16 20-25-32.png">

<img width=“300” src="Readme_images/Bildschirmfoto vom 2020-10-16 20-25-55.png">

And convert back to JabRef Reference
<img width=“300” src="Readme_images/Bildschirmfoto vom 2020-10-16 20-31-34.png">

... you just need to refresh the database from within JabRef now.

