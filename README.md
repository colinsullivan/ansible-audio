ansible-audio
=========

Builds jackd and configures kernel audio priority.  Currently intended for use on a headless raspberrypi, hence the default of building jackd from source without dbus.

Role Variables
--------------

If this is building for a raspberry pi
`audio_raspberrypi: false`

If the fepi driver configuration should be used
`audio_raspberrypi_fepi: false`

If the generic onboard audio from raspberry pi should be disabled
`audio_raspberrypi_disable_onboard_audio: true`

Switch the amount of video memory for the pi
`audio_raspberrypi_gpu_mem_mb: 16`

Build jackd from source
`audio_build_jackd: false`

Install jackd from apt (switch to `jackd1` to install Jack 1)
`audio_jackd_version: jackd2`


License
-------

MIT

Author Information
------------------

[colin-sullivan.net](http://colin-sullivan.net)
