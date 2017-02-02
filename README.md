[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/check_resque_paranoid.svg)](https://hub.docker.com/r/rubygem/check_resque_paranoid/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/check_resque_paranoid.svg)](https://hub.docker.com/r/rubygem/check_resque_paranoid/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/check_resque_paranoid.svg)](https://hub.docker.com/r/rubygem/check_resque_paranoid/)
[![Gem Downloads](https://img.shields.io/gem/dt/check_resque_paranoid.svg)](https://rubygems.org/gems/check_resque_paranoid/)
# check_resque_paranoid

Auto-Generated Docker image for check_resque_paranoid to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/check_resque_paranoid`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/check_resque_paranoid`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/check_resque_paranoid`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/check_resque_paranoid/)
