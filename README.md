# wordpress-docker

A `docker-compose` 3.7 setup for Wordpress.
Contains `mysql:8` and `adminer:latest`.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What you will need:

```
$ docker
$ docker-compose
```

### Installation

* Put your plugins in the `plugins` folder
* Put your themes in the `themes` folder
* Put uploads in the `uploads` folder
* Run the development environment:
```
$ docker-compose up --build -d
```
* Visit `http://localhost:8001` in a web browser to execute the Wordpress installation
* Visit `http://localhost:8002` for Adminer

## Deployment

Coming soon...

## Versioning

We use [SemVer](http://semver.org/) for versioning. 

## Authors

* **HankEye** - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Links

* [Tutorial on gridscale.io](https://gridscale.io/community/tutorials/dockerize-wordpress-docker-compose/)
* [Offical Docker docs](https://docs.docker.com/compose/wordpress/)
