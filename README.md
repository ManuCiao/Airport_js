# Airport Challenge

Airport Challenge rewritten in Javascript and Jasmine @Makers Academy during the 5th week.


## Challenge setup

The specification for the Airport challenge can be found [here](https://github.com/makersacademy/airport_challenge).
My Ruby solution of this challenge you can find it [here](https://github.com/ManuCiao/airport_challenge).


## Tasks

```
As an air traffic controller 
So I can get passengers to a destination 
I want to instruct a plane to land at an airport and confirm that it has landed 

As an air traffic controller 
So I can get passengers on the way to their destination 
I want to instruct a plane to take off from an airport and confirm that it is no longer in the airport

As an air traffic controller 
To ensure safety 
I want to prevent takeoff when weather is stormy 

As an air traffic controller 
To ensure safety 
I want to prevent landing when weather is stormy 

As an air traffic controller 
To ensure safety 
I want to prevent landing when the airport is full 

As the system designer
So that the software can be used for many different airports
I would like a default airport capacity that can be overridden as appropriate
```

## Instructions

To get started, go to the [latest build page for Jasmine](https://github.com/jasmine/jasmine/releases) and download the most recent standalone version in a zip file.

Once you have downloaded the `.zip` archive, copy it to your FizzBuzz project file (assuming you are currently in the directory) and extract it:

```sh
cp -r ~/Downloads/jasmine-standalone-2.3.4.zip .
unzip jasmine-standalone-2.3.4.zip
```
To see the test cases you need to run on your command line once you are in the folder that contain the project:

```
open SpecRunner.html
```

I used a random number generator (_Math.random()_) to set the weather (it is normally sunny but on rare occasions it may be stormy).



