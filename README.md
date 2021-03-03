# The Multi-Searcher v1.1

Bash shell script used for searching a server on the network and inside host files on the workstation.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- unix based working env
- mlocate package - use yum install/apt-get install to install this package
- openssh package - same as above

### Installing

1. Cloning the project to you local workstation:

```
git clone git@github.com:zakarel/Multi-Searcher.git
```
2. Add execute permission to the deployment script:

```
chmod +x search.sh
```

## Using the script

```
./search.sh [hostname/filename]
```

## Authors

* **Tzahi Ariel** - *Initial work* - [zakarel](https://github.com/zakarel)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
