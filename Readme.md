# GHCJS Dockerfile
Dockerfile for building a ghcjs environment from a http://ghcjs.luite.com package.

The code is adapted from https://github.com/flipstone/docker-ghcjs. Many thanks to them!
This Dockerfile uses the official haskell:8 image together with the latest ghcjs/ghc-8.0 package from http://ghcjs.luite.com.

`ghcjs-boot` is executed during image creation, so building it takes a long time (perhaps hours depending on your machine).
