# UTF-8 Subtitles Converter

This project is a highly configurable [Plex Media Server](https://plex.tv/) plug-in (based on SRT2UTF-8) for converting subtitles to the more Plex friendly UTF-8 encoding.
Plex has a hard time displaying diacritics and other special characters when the subtitles are not UTF-8 encoded. This plug-in resolves this issues by automatically converting all the scanned subtitle files to UTF-8 encoding, which are fully supported by Plex.

## Installation

Download the latest release and extract all its content (the folder UTF-8SubtitlesConverter.bundle) to [Plex Plug-in folder](https://support.plex.tv/hc/en-us/articles/201106098-How-do-I-find-the-Plug-Ins-folder-).
*In order to avoid having to refresh the libraries after conversions make sure the UTF-8 Subtitles Converter is the first in the order of priority. That is needed in order to force conversion and then scanning for metadata. That is important when you choose to create a new subtitles file and not update the old one.*

## Usage

UTF-8 Subtitles Converter will automatically detect if subtitles are not UTF-8 encoded and convert them (either in-place or to a new file). Use the Agent's options to define whether to use a new file or not and to choose the default language which will be used to create the filename. 

## Contributing

Please feel free to fork this project and implement whatever you want (in fact this is how this project was created). If you feel the change you did may bring a benefit to this project submit a pull request and I'll consider merging the changes.

## Change log

Read the [change log](/Release files/Change log.txt) for a full list of changes.

## Credits

All the credits (and more ) muust go to [Tommy Mikkelsen](https://github.com/ukdtom) for his [SRT2UTF-8.bundle](https://github.com/ukdtom/SRT2UTF-8.bundle). I only added a few more options, did more validations and packaged everything up nicely.

## License

This program is free software: you can redistribute it and/or modify it under the terms of the [GNU General Public License](http://www.gnu.org/licenses/) as published by the Free Software Foundation, either version 3 of the License, or any later version.
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](http://www.gnu.org/licenses/) for more details.