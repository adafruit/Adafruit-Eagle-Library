## Adafruit Eagle Library

Now in Eagle 6 format!

### Don't click on the files! 

[Click here](https://github.com/adafruit/Adafruit-Eagle-Library/zipball/master) 
to download this as a zip file.

### Installation

1. Open Eagle and select the `Control Panel` window.
2. Choose `Options` and from the drop down that appears, `Directories`.
3. Change the Libraries line from: `$EAGLEDIR/lbr` to something like:

    > $EAGLEDIR/lbr:$HOME/external_lbrs (for OS X)

    > $EAGLEDIR\lbr;$HOME\external_lbrs (for Windows)

4. Click `OK` to save your changes.
5. Eagle will prompt to create the directory if it does not already exist. Note 
the location and choose `Yes` to create the directory.

    > On OS X, `$HOME/external_lbrs` changes to: /Users/mosfet/external_lbrs/
    
    > On Windows, `$HOME\external_lbrs` changes to: C:\Users\Mosfet\Documents\external_lbrs

6. Find and open the `external_lbrs` folder. Unzip and drag `adafruit.lbr` into the 
   new `external_lbrs` folder.
7. Restart Eagle. The library should be now be usable. 
