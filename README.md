- Download the script  patch-edid.rb

- manually create /Library/Displays/Contents/Resources/Overrides directory
- Copy the script to /Library/Displays/Contents/Resources/Overrides
- Make sure your dvi port is connected at this point
- Open terminal, cd  /Library/Displays/Contents/Resources/Overrides
  and execute the script
\\\\\\\\\\\\\\\\\\\\\\\\\\
ruby patch-edid.rb
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

- This should create DisplayVendorID-xxxx folder in /Library/Displays/Contents/Resources/Overrides
- disconnect the dvi and reconnect
- done
