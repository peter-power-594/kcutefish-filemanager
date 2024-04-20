# File Manager

Cutefish File Manager, simple to use, beautiful, and retain the classic PC interactive design.

![screenshot](screenshots/Screenshot_20211025_151224.png)

## OpenMandriva Dependencies

```shell
sudo dnf in task-develop
sudo dnf install extra-cmake-modules lib64KF5KIO-devel

```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## Uninstall

```shell
rm /usr/bin/cutefish-filemanager
rm /usr/share/applications/cutefish-filemanager.desktop
```

## License

This project has been licensed by GPLv3.
