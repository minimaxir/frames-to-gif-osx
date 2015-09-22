# Convert Frames to GIF on OS X
An application that allows the user to easily convert frames to very-high-quality GIFs on OS X. 

![](/examples/uni_frames.gif)
![](/examples/bi_frames.gif)

The tool is used with a folder containing procedually-generated frames, named in *lexigraphical order*. The primary intent is for use with statistical visualizations.

The [Convert Frames to GIF App Custom tool](https://github.com/minimaxir/frames-to-gif-osx/blob/master/Convert%20Frames%20to%20GIF%20App%20Custom.zip) also lets you specify maximum width, frame rate, and # of colors for the output GIF, which is good for managing file size as well as usability.

## Installation

*Note: Installation may have issues depending on system config, particularly step #2. If you run into issues, let me know.*

1. Open up Terminal and install [Homebrew](http://brew.sh) by running this command and following the instructions:

		ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
		
2. Install the two GIF-making applications using this Homebrew command:

		brew install ImageMagick gifsicle

3. Download the App from the repository, unzip and run it, selecting the folder containing the frames when prompted.


## Known Issues

* No sanity check for input validation yet. (e.g. don't increase the frame rate beyond 60fps or bad things happen)
* No tests.

## Maintainer
* Max Woolf [(@minimaxir)](http://minimaxir.com)

