# ovos-binary-shop
Wheels and pre-compiled binaries for usage with ovos plugins / images


see releases for downloadable files


## Python 3.10

- [tflite-runtime aarch64](https://github.com/OpenVoiceOS/ovos-binary-shop/releases/tag/tflite-runtime_python_3.10_aarch64.whl)


## Python 3.11

- [tflite-runtime aarch64/armv6l/armv7l/x86_64](https://github.com/OpenVoiceOS/ovos-binary-shop/releases/tag/tflite-runtime_python3.11_linux_aarch64%2Farmv6l%2Farmv7l%2Fx86_64.whl)
- [onnxruntime-x86_64.whl ](https://github.com/OpenVoiceOS/ovos-binary-shop/releases/tag/tflite-runtime_python3.11_linux_aarch64%2Farmv6l%2Farmv7l%2Fx86_64.whl)


### PKGBUILDS

PKGBUILDS generated via https://github.com/anntzer/pypi2pkgbuild

each directory in this repo is a package

#### Dependency Build Tree:

*WIP* List order in which to build the pkgbuilds

*For Testing*:
- git clone https://github.com/OpenVoiceOS/ovos-binary-shop into a clean chroot / os environment
- cd ovos-binary-shop/python-$pkgname
- makepkg -si ("s" will resolve dependencies from AUR and Manjaro Repos, "i" will install them as official packages via pacman)

```
python-memory-tempfile
python-combo-lock
python-json-database
python-kthread
python-ovos-utils

python-mycroft-messagebus-client

python-ovos-backend-client
python-rich-click
python-ovos-config

python-quebra-frases
python-ovos-lingua-franca

python-langcodes
python-ovos-bus-client
python-ovos-plugin-manager

python-ovos-workshop

python-simplematch
python-padacioso

python-ovos-core
python-ovos-gui
```
