# [alpha] Stream Music Recognition

A simple Python wrapper around C++ Gracenote SDK (GNSDK).  
Currently in alpha/experimental stage, so anything could change in the future.

## Building
1. `cp make_config.py.example make_config.py`
2. Edit the config file.
3. `make`

## Running the example (main.py)
1. `cp make.py.example make.py`
2. Edit the config file.
3. `python3 main.py *stream-url-or-file-path* | python3 viewlog.py` (a bit awkward for now).