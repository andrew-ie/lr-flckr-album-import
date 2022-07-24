# Lr-Flickr-Album-Import
Plugin to take exported metadata from Flickr and convert it to collections in Lightroom

## Installation Instructions

In the Lightroom Plugin Manager, add `lr-flickr-album-import.lrdevplugin` as a plugin point.

## Usage Instructions

1. Go to [Your Flickr Account page](https://flickr.com/account), and select "Request my Flickr data"
2. Download and decompress the resulting files
3. Import the photos themselves manually
4. Launch this plugin - select the `metadata` folder. This is the folder from the downloaded data that contains the `albums.json` file and similar .json files for each photo

It is recommended to perform this on a new empty Catalog - it will then create a new set of collections that match the albums that were present in Flickr.
