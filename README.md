# Creating-datasets-for-machine-learning

This repository contains some scripts that I have used for data collection from web for my machine learning projects. Feel free to send me a pull request if you want to add on to this.

## Image Datasets

#### Road image dataset from Open Street Cam [notebook](https://github.com/muaz-urwa/Creating-datasets-for-machine-learning/blob/master/Create%20road%20Image%20Dataset%20from%20Open%20Street%20Cam.ipynb)
This notebook does the following:
- Get geo coordinates along the roads in New york from new york streets shape file
- Uses these coordinates to extract relevant track ids from open street cam
- Extracts and saves images from these track ids.

#### Road image dataset from Google Street View [notebook](https://github.com/muaz-urwa/Creating-datasets-for-machine-learning/blob/master/Create%20road%20image%20dataset%20from%20Google%20Street%20View.ipynb)
This notebook does the following:
    - Get geo coordinates along the roads in New york from new york streets shape file
    - Uses these coordinates to extract images from google street view

#### Get Faces from Flickr based on Geolocation [notebook](https://github.com/muaz-urwa/Creating-datasets-for-machine-learning/blob/master/Get%20%20Flickr%20Faces%20by%20GeoLocation.ipynb)
This notebook does the following:
    - Gets images for the locations specified below
    - Saves the images temporary in temp directory specified below
    - Uses Dlib to filter images with faces
    - Stores the filtered images in processed directory
    - A directory of images is created for each of the locations

## Text Datasets

#### Tweet Data Collection [notebook](https://github.com/muaz-urwa/Creating-datasets-for-machine-learning/blob/master/Collect%20Tweets%20%20by%20Location.ipynb)
This notebook does the following:
    - Collects the twitter data from the bounding box of geo-cordinates specified below.
    - Outputs the twitter data in the json output file specified below.

#### Create text dataset of Wikipedia articles for specific topics [notebook](https://github.com/muaz-urwa/Creating-datasets-for-machine-learning/blob/master/Create%20text%20dataset%20of%20Wikipedia%20articles%20for%20specific%20topics.ipynb)
This notebook does the following:
    - Creates a list of topics of interest by parsing json. (use your own list)
    - Extracts and saves wikipedia articles about the topics

## Other

#### Get data about businesses using Yelp [notebook](https://github.com/muaz-urwa/Creating-datasets-for-machine-learning/blob/master/Get%20data%20about%20business%20using%20Yelp.ipynb)
This notebook does the following:
    - Loads the locations of bars in Manhattan from a file
    - Uses geo search on Yelp API to identify the bar and get information about price and rating



