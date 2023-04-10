# Touchdesigner_Toolbox
A public toolbox of different helpful add-ons for touchdesigner.

## Projector Tools

This container provides a few basic tools for projection. Given the projector res, the plate res, and the desired content, it will make a test plate at the desired res, and fit the content plate to the projector res before a stoner. Outputs for this container are full black, full white, full custom projector color, test plate, and content. There are also options to comp the Spectra Logo over the output and open the stoner window easily.\
**note:** Stone from the edges with this setup, do not create columns to match with plate output\
**note:** This file includes the Script Tester (see below)

## Script Tester

The script tester is a tool to easily trigger scripts. It was made for parent extensions, but can be used to trigger virtually any script.

## Test Plate

Given a resolution, this tool will output a test plate of circles and lines to help set up and calibrate multiple projectors.

## Corner Pinner UI and Image Processing

These tools are made to be used together. Given an image (such as a camera feed), you can use the Corner Pinner UI to easily select the corners of the wanted area, which will feed that data to the corner pinner (set to extract) inside the Image Processing tox
