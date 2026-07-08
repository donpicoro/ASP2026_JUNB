# Simple examples on `Jupyter notebook`

Here you have the source code of a very basic `jupyter notebook`

## How to get this code

To get this into your computer, just clone this repository to your local machine

```sh
git clone https://github.com/donpicoro/ASP2026_JUNB.git
```

## How to run

Assuming you have a working `python` installation, this should work.

```sh
jupyter notebook
```

This should bring up a browser which allows you to explore the files under the current directly and below.

If you click on a file it will open it ready for editing and running it.

### In case of error because of missing packages or dependencies

It is possible that your specific machine

```sh
pip install scipy
pip install ipywidget
pip install ipympl
```

if the lines above do not work (laptops typically as they were set up differently than desktops), try running this first:

```sh
source ~/.venv/bin/activate
```

then execute the `pip install` lines above