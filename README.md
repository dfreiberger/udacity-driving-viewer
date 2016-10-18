# udacity-driving-viewer

Scripts to playback data created by https://github.com/rwightman/udacity-driving-reader

## Installation

Checkout this code and run the one and only script

## Usage

First use the "bagdump.py" script at https://github.com/rwightman/udacity-driving-reader to generate a folder with left, right and center images and corresponding steering.csv and camera.csv file.

	python bagdump.py -b ./dataset.bag -o ./output -d

Then, run the playback.py script with arguments to playback the three camera views, along with overlaid status from the steering.csv file.
	
	python playback.py -i ./output/dataset
