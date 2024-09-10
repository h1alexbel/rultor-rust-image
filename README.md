[![docker](https://github.com/h1alexbel/rultor-rust-image/actions/workflows/docker.yml/badge.svg)](https://github.com/h1alexbel/rultor-rust-image/actions/workflows/docker.yml)
[![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/h1alexbel/rultor-rust-image)](https://hub.docker.com/r/h1alexbel/rultor-rust-image)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/h1alexbel/rultor-rust-image/master/LICENSE.txt)

This is the lightweight Docker image for [Rultor](https://www.rultor.com)
supplied with Rust, NodeJS, Java. Available in Docker Hub as
[`h1alexbel/rultor-rust-image`](https://hub.docker.com/r/h1alexbel/rultor-rust-image).

Use it like that in your `.rultor.yml`:

```yml
docker:
  image: h1alexbel/rultor-rust-image:0.0.1
```

This image has Ubuntu 22.04 and the following packages, in their latest versions:

* Git
* sshd
* Java
* Maven
* NodeJS
* Rust and Cargo

Feel free to add yours by submitting a pull request.
