# Bookworm [![Translation status](https://hosted.weblate.org/widgets/bookworm/-/svg-badge.svg)](https://hosted.weblate.org/engage/bookworm/?utm_source=widget) [![Build Status](https://travis-ci.org/babluboy/bookworm.svg?branch=master)](https://travis-ci.org/babluboy/bookworm)
A simple, focused eBook reader

Author: Siddhartha Das

Read the books you love without having to worry about the different format complexities like epub, pdf, mobi, cbr, etc. This version supports EPUB, PDF and Comics (CBR and CBZ) formats with support for more formats to follow soon.

Check the Bookworm website for details on features, shortcuts, etc. : https://babluboy.github.io/bookworm/

## How to install bookworm:

```shell
sudo add-apt-repository ppa:bookworm-team/bookworm
sudo apt-get update
sudo apt-get install bookworm
```

## How to build bookworm:

```shell
sudo apt-get build-dep granite-demo 
sudo apt-get install libgranite-dev
sudo apt-get install valac
sudo apt-get install libwebkit2gtk-4.0-37 libwebkit2gtk-4.0-dev
sudo apt-get install libsqlite3-dev
sudo apt-get install poppler-utils libpoppler-glib-dev

git clone https://github.com/babluboy/bookworm.git
cd bookworm
mkdir build && cd build 
cmake -DCMAKE_INSTALL_PREFIX=/usr ../
make
sudo make install
```
## Screenshots

![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/BookwormLibraryView.png)
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/BookwormReadingView.png)

Two Page View
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/TwoPageView.png)

Bookworm Dark Mode
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/DarkModeLibraryView.png)
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/DarkModeReadingView.png)

Library List View
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/LibraryListView.png)

Bookworm Preferences
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/PreferencesDialog.png)

