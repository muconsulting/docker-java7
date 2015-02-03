#Ubuntu Dockerfile

A Dockerfile that produces a Docker Image for [Oracle Java 7](http://www.oracle.com/).

## Usage

### Build the image

To create the image `muconsulting/java7`, execute the following command on the `docker-java7` folder:

```
$ docker build -t muconsulting/java7 .
```

### Run the image

To run the image:

```
$ docker run -ti --rm --name java7  muconsulting/java7
```

## Copyright

Copyright (c) 2015 Sylvain Gibier. See [LICENSE](https://github.com/muconsulting/docker-java7/blob/master/LICENSE) for details.
