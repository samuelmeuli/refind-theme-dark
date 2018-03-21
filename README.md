# rEFInd Dark Theme

A simple, dark theme for the [rEFInd boot manager](http://www.rodsbooks.com/refind).

![Screenshot](screenshot.png)


## Installation

1.  Mount your EFI partition (macOS: `sudo mount -t msdos /dev/disk0s1 /Volumes`)
2.  Open the rEFInd directory (macOS: `cd /Volumes/EFI/rEFInd`)
3.  Create the folder `themes` if it doesn't already exist
4.  Clone this repository into the `themes` folder
5.  Activate the theme by adding `include themes/refind-theme-dark/theme.conf` to the `refind.conf` file


## Contributing

If you have a request for a new icon, please either follow the steps below (you'll need [Affinity Designer](https://affinity.serif.com/designer)) or create an issue with an URL to the icon (in SVG format).

1.  Add the SVG file of the new icon to `icons/originals`
2.  Add the source of the file to `icons/sources.txt`
3.  Using Affinity Designer, create a new artboard for the icon in `icons/icons.afdesign` and export it as a PNG file to `icons/output`
4.  Create a PR


## Credits

This theme was inspired by the [Minimal](https://github.com/EvanPurkhiser/rEFInd-minimal) and [Ambience](https://github.com/lukechilds/refind-ambience) themes for rEFInd.
