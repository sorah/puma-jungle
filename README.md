# Yet Another Puma Jungle

inspired by https://github.com/puma/puma/blob/master/tools/jungle, rewritten by scratch.
but differ at:

* configuration file is separatedly by app: `/etc/puma/<app_name>`

  * for easier managing by puppet, chef, etc.

* Not require `lsb-functions`, you just need only `start-stop-daemon`

  * Works with no modification on Gentoo!

## install

```
cp puma /etc/init.d/puma
cp run-puma /usr/local/bin/run-puma
```

## license

Public Domain

## Author

Shota Fukumori (sora\_h) <her@sorah.jp>
