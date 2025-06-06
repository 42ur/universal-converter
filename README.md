# Universal Converter
## A universal converter for macOS supporting images, videos, documents and fonts

Works as an Automator service : just right-click a file in the Finder, and you'll be able to convert it to plenty of formats. Basically a ffmpeg/magick/pandoc/fontforge wrapper, but makes converting files easy and native-like. Not a very complex project, but it saves a lot of time, runs locally (unlike the mainstream alternatives, like Cloudconvert) and it's quite a shame that macOS isn't able to do that natively.

https://github.com/user-attachments/assets/4906d1e3-bc1d-493d-b11b-0647d2dc69c6

Available in both French and English.

## How to use
- [Download](https://github.com/42ur/universal-converter/raw/refs/heads/main/Convert.workflow.zip) "Convert.workflow", open it and install the quick action
- Make sure that you have magick, ffmpeg, pandoc and fontforge installed!
  - If you don't have [Homebrew](https://www.brew.sh), install it by running `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
  - Install the required dependencies by running `brew install ffmpeg imagemagick pandoc fontforge`
- Right-click a file in the Finder, go to "Quick actions" and click "Convert"

Feel free to fork this project, to report any bug and to suggest enhancements! This project is a very simple one and i'm still kinda a beginner, I'll be happy to hear your thoughts.
