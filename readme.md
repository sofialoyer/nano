# Trash Identification

 Searches images and looks for trash.  This could be used to help clean up trash on the side of roads using Google Street View or similar image databases.  Future version could allow volunteers to sign up for specific zip codes and be alerted when trash is identified.  The geolocation from the image could be used to let the volenteer know where the trash is located.  Once they clean up the trash, they could report back that it was cleaned and when.  

![Searching for trash](https://i.imgur.com/5vy0jBv.jpeg)

## The Algorithm

The project uses DetectNet (https://github.com/dusty-nv/jetson-inference/blob/master/docs/detectnet-console-2.md) to find trash in images.  

## Running this project

1. Download the project and resources files
2. Make sure to have DetectNet installed
3. Run the following command:   python3 code.py

[This is a link to my intro video](https://youtu.be/7V-a8HBzB9c)
