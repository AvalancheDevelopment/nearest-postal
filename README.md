# Nearest Postals

This script displays a nearest postal next to where PLD would go and also has a command to draw a route to a specific postal. Original script by [blockba5her](https://github.com/blockba5her/nearest-postal).

## Installation

1. There are 2 ways to install it, and I recommend the first
    1. Run the following command in a terminal
        - `git clone https://github.com/AvalancheDevelopment/nearest-postal.git`
    2. Download the code from the [GitHub] (https://github.com/AvalancheDevelopment/nearest-postal/archive/master.zip)
2. As of now, this script supports 3 postal maps. From what I have seen, these are the most popular
    - `new-postals.json` -> [New and Improved Postals](https://forum.fivem.net/t/release-postal-code-map-new-improved-v1-1/147458)
    - `old-postals.json` -> [Original Postals](https://forum.fivem.net/t/release-modified-street-names-w-postal-numbers/8717)
    - `ocrp-postals.json` -> [OCRP Postals](https://forum.fivem.net/t/release-ocrp-community-releases/166277)

## Command

To draw a route to a certain postal, type `/postal [postalName]` and to remove just type `/postal`

It will automatically remove the route when within 100m of the destination


## San Andreas Police Radio Setup
To properly set up this script, all you need to do is put `nearestPostal` in the config.json file in the sapr directory for the 'NearestPostalEvent'.
