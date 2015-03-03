# PHP Images for drone.io CI
Drone requires git to be installed in an image. The standart PHP images do not come with git - so that's what this is about!

Note that only a very small subset of all PHP versions are supported - feel free to contribute if you need one that does not yet exist.

# Currently supported versions
* 5.4.33, 5.4.33-minimal
* 5.5.20, 5.5.20-minimal

# What's included?
The minimal images (with the `-minimal` suffix) inherits from the php docker image. It only installs git (which is the minimal requirement for drone)
The images without the `-minimal` prefix have also the latest version of composer and phpunit installed. This makes your builds faster and cleaner since they do not have to download these tools every thime.
