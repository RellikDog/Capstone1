# Capstone1
Project exploring links between NICS(firearm background checks) trends and state populations.

### Team:

- Richard Bellamy

## Data
Credit to Buzzfeed for their opensource data parser
Download NICS data at
 - https://github.com/BuzzFeedNews/nics-firearm-background-checks
Used data in accordance with MIT license


Population density density came from 
 - https://randstatestats.org/us/stats/historical-population-density-(states-only).html

### Problem Domain
Given the knowledge of aproximatly how many background checks were conducted for each type of firearm in each state by year and the population densities of each state by year, do any trends emerge about the types of firearms that background checks are for and the frequency they are requested in comparrison the the states population density?

### Methodology
The NICS data has columns for handgun, long_gun, and other as well as columns for all 3 with various prefixes such as 'prepawn', 'redemption', and 'private sale'.  For the purpose of this study I agregate the sums of these columns into 3 coloumns handgun, long_gun, and other. I'm going to further eliminate the 'other' and 'multiple' coloumns because they aren't pertinent to my experiment.

### Hypothoesis
A) I predict that states with a higher population density will have more checks for handguns overall, but will be lower in terms of checks for handguns by population density.

B) I also predict that states with lower population density will have higher occurences of long gun applications

C) I predict that the ratio of handgun to long gun applications will vary in accordance with state population variations

### Prerequisites

- Python 3

```
$python --version
Python 3.7.4
```

- NICS data from data section
Follow link and move file from data folder to folder named data in this repositories root directory

- Population density information
Needs to be in same data folder


===========================================================V TEMPLATEING IDEAS V===================================================

I'm chosing to look at data from 1999 through 2018.  This is because my population density data ends in 2018 and my NICS data begins at the end of 1998.  This is also because that is a 20 year span and I like round numbers.
### Installing  

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc


