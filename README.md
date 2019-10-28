# OE Unit Tests

This repo hosts unit tests for the Open Ephys plugin-GUI.

The motivation is to have ground truth based signal chains with known input/output data in order to validate code development. 

Each unit test is structured as follows:
- Contained in a folder that describes what the unit test is validating.
- Contains a settings XML file used to load the desired signal chain into the GUI.
- Contains a bash/bat file used to run the desired test and report the results.