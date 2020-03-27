This README file contains information on the contents of the meta-rpi3 layer.

Please see the corresponding sections below for details.

Dependencies
============

  URI: meta-raspberrypi
  branch: zeus

  .
  .
  .

Patches
=======

Please submit any patches against the meta-rpi3 layer to the maintainer:

Maintainer: Amr Abdelghafar <amr.t.abdelghafar@gmail.com>

Usage
=================================================

Run 'TEMPLATECONF=../meta-rpi3/conf'
Run 'source oe-init-build-env build-rpi3'
Run 'bitbake core-image-base'
Run 'sudo dd if=core-image-base-raspberrypi3.rpi-sdimg of=/dev/mmcblk0 status=progress'
