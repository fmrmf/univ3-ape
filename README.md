# univ3-ape

Charts for Uni V3 using ApeWorX

## Setup

Install [`eth-ape`](https://github.com/ApeWorX/ape) and other deps in a virtual environment

```sh
# create and load a virtual environment
python3 -m venv venv
source venv/bin/activate

# install the developer dependencies
pip install -r requirements-dev.txt
```

and install the ape plugins needed to run notebook

```sh
(venv) ape plugins install .
```

then run [`ape-notebook`](https://github.com/ApeWorX/ape-notebook)

```sh
(venv) ape notebook
```
