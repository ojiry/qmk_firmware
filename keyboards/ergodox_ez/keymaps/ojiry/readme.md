# OJIRY'S KEYMAP

## Using Docker in Builds

```sh
$ docker build -t ojiry/qmk_firmware .
$ docker run -e keyboard=ergodox -e subproject=ez -e keymap=ojiry --rm -v $('pwd'):/qmk:rw ojiry/qmk_firmware
```
