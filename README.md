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

If you click on a file it will open it ready for editing and running it. You run each cell by pressing "shift + Enter"

There are menus on the top part for saving, renaming, runnning, etc. Feel free to explore your options.

### In case of error because of missing packages or dependencies

In the event that you run into problems when running the notebooks because a module is not found, this means it is not installed on your machine or environment.

There are (at least) two ways to install packages (modules) in your machine or environment

#### Installing on a terminal

This is the most straightforward way, just open up a terminal and issue a command like follows. For instance to install a package called `<module name>` do this:

```sh
pip install <module name>
```

so, in concrete, to install packages like `scipy`, `ipywidget`, and `ipympl`:

```sh
pip install scipy
pip install ipywidget
pip install ipympl
```

you could also install them all in one command like this

```sh
pip install scipy ipywidget ipympl
```

For those onsite at CEMASTEA Nairobi, Kenya: if the lines above do not work (laptops typically as they were set up differently than desktops), try running this first:

```sh
source ~/.venv/bin/activate
```

then execute the `pip install` lines above