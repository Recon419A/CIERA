# CIERA Wireless Printer Configuration
## Windows
1. Click the `Start` menu, then choose `Settings`
2. Click `Devices` and ensure `Printers and Scanners` is selected on the left-hand side
3. Click `Add a printer or scanner`
4. Wait briefly for the option to appear, then click `The printer that I want isn’t listed.`
5. Select `Add a printer using a TCP/IP address or hostname` and click next
6. Type in 129.105.79.70 for the color printer, or 129.105.79.250 for the black and white printer in the field called `Hostname or IP Address`, then click next
7. Installation should now proceed

## macOS
1. Go to System Preferences
2. Click `Printers and Scanners`
3. Click `+` at the bottom left under `Printers`
4. Click `IP` at the top
5. Enter the IP (129.105.79.70 for the color printer or 129.105.79.250 for the black and white).
6. Click Add
7. Check `Duplex Printing Unit`
8. Click OK
9. Control-Click on the printer and select rename
10. Enter a name that you will remember
11. Hit OK

## Ubuntu
### Color Printer
#### With Generic Driver
 1. Open System Settings
 2. Click `Printers`
 3. Click `Add`
 4. Select `Enter URI` in the menu at left
 5. Type "ipp://129.105.79.70" and click `Forward`
 6. On the `New Printer` page choose `Select printer from database` and choose `Generic`
 7. Click `Forward`
 8. Choose `PostScript` at left and then `Generic PostScript Printer Foomatic/Postscript [en]`
 9. Click `Forward`
 10. Choose names and locations that make sense and click `Forward`
 11. The printer should now be set up. You may optionally print a test page to verify that this is the case.

#### With Manufacturer's Driver
 1. Obtain the correct driver (can be obtained from Box, Google Drive, or by searching on the Manufacturer's web site)
 2. Open System Settings
 3. Click `Printers`
 4. Click `Add`
 5. Type "ipp://129.105.79.70" and click `Forward`
 6. Select `Provide PPD file` and select the appropriate file using the dialog box, then click `Forward`
 7. Click `Forward`
 8. Click `Apply`
 9. The printer should now be configured. Optionally, print a test page.

### Black and White Printer
 1. Open System Settings
 2. Click `Printers`
 3. Click `Add`
 4. Select "Enter URI" in the menu at left
 5. Type "ipp://129.105.79.70" and click `Forward`
 6. Select `Select printer from database` and choose `HP`, then click `Forward`
 7. On the left, select `LaserJet p4015n` and click `Forward`
 8. Check `Duplexer installed` and click `Forward`
 9. Click `Apply`
 10. The printer should now be configured. Optionally, you may print a test page to verify that it is set up correctly.
