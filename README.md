# salesforce-lead-zurb
Uses ZURB Foundation with a Salesforce Lead form

Adds Google geocoder when the form loads.

Also added ParsleyJS validation to require fields to be filled in with 'parsley-required="true"' on each input and make sure phone and email are in acceptable formats..

This is great for mobile lead collection (door-to-door) with a smartphone.

Literally boils a lead interaction down to "Hi, what's your name, phone and email?".

Form is automatically mobile-friendly due to ZURB Foundation, fits any screen out of the box.

All libraries are from CDNJS (Thanks CloudFlare!) so everything works out of the 1 index.html file.

Location may not work from the local file. For Chrome, make a shortcut and add this to the end of the Target line:  --allow-file-access-from-files

Sample at http://dkdevwrx.github.io/salesforce-lead-google-geocoder.
