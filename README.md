# BikePosition

## Purpose
Jupyter Notebook script for the analysis of triathlete's position on a triathlon bike.
The script allows the user to:

* Import a video
* Move from frame to frame
* Draw points and lines to measure important angles
* Save images with the above-mentioned drawings

## Interface

The interface looks as follows:

![GUI][docs/interface.png]

The two sliders on the sides of the image, serve as controllers to move the selected
point to a desired location, so as to measure desired angles.


## Future developments

The tool is still in it's rudimentary form, the following features are currently envisioned and will be implemented over time:

* automatic recognition of important points in the frame (foot, ankle, knee, hip, shoulder, elbow and hands)
* automatic and continuous measurement of multiple angles
* time series of tracked angles
* integration of power and cadence data from .fit activity files

The tool is stored at the following link: https://github.com/matteobe/BikePosition, in case you want to contribute, reach out on GitHub.

## License

The licensing of this project is regulated as detailed in the attached MIT License.

Enjoy!
