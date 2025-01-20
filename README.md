# wis2box-release

This repository the images version used by the various services that compose a wis2box-release.

The images are tracked within the file `docker-compose.images.yml` that sets the images to be used for each dockerized service within the wis2box-stack.

The `wis2box-ctl.py`-script included in the wis2box-repository will reference `docker-compose.images.yml` from this repository to determine which images are to be used.

When new images are published containing security updates or bug fixes, the `docker-compose.image.yml` file is to be updated and a new wis2box-patch-release can be published.

Please contact the wis2box-development team when you believe a new patch-release for the wis2box is required.
