# Unity Indicator for LTE Volume for Vodafone B3000

This is a small indicator for the Unity desktop that will show the current used volume from your Vodafone B3000 LTE modem. It will additionally notify about new SMS.

## Depdendecies

Matplotlib is used to draw a graph of the used volume. Install with
```
    pip3 install matplotlib
```

## Usage

Run the programm, it will automatically try to get the data from the router running as vodafonemobile.cpe. If you want to configure it to use a differnt hostname, you will have to quit and edit the configuration file by hand (see TODO). The configuration file is located at ~/.config/indicator-lte-volume.ini.

You can change the displayed value via the menu, available options are

- Up and down volume
- Summarized volume
- Up, down and summarized volume

## TOOD
- Configuration dialog
- Better graph
- If possible: Add functionality to reset volume to zero
