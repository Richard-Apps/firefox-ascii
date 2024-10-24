# Firefox-ASCII
A simple userContent.css file to edit the appearance of the new-tab in Firefox.

## Preview
![preview](/assets/preview.gif)

## How to use
1. * Type ```about:config``` in the address bar and press Enter.
   * In the search bar, type ```toolkit.legacyUserProfileCustomizations.stylesheets```.
   * Set the value to ```true``` by double-clicking the setting.

2. * Type ```about:support``` in the address bar and press Enter.
   * Under the "Application Basics" section, find Profile Folder and click on the "Open Folder" button next to it.

3. * Create a "chrome" folder inside the profile folder if it doesn't exist already.
   * Download the [userContent.css](userContent.css) file and put it inside the "chrome" folder.

4. * Restart Firefox for any changes to take effect.

## Roadmap
- [ ] Tidy up the file, needs refinement
- [ ] Add customization options