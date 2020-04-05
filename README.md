# Capstone1
    Project exploring links between NICS(firearm background checks) trends and state populations.

### Team:

- Richard Bellamy

## Problem Domain
    Given the knowledge of aproximatly how many background checks were conducted for each type of firearm in each state by year and the population densities of each state by year, do any trends emerge about the types of firearms that background checks are for and the frequency they are requested in comparrison the the states population density?

### Methodology
My Nics data has columns for handgun, long_gun, and other as well as columns for all 3 with various prefixes such as 'prepawn', 'redemption', and 'private sale.  For the purpose of this study I agregate the sums of these columns into 3 coloumns handgun, long_gun, and other.

### Hypothoesis
- I predict that states with a higher population density will have more checks for handguns overall, but will be lower in terms of checks for handguns by population density.

- I also predict that states with lower population density will have higher occurences of long gun applications

### Prerequisites

- Python 3

```
Give examples
```
===========================================================V TEMPLATEING IDEAS V===================================================
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


