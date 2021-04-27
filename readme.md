# Python minecraft client packager

Python minecraft client packager - is universal generator of clients, any version of minecraft.
The script is extremely lightweight and works very fast, especially at the stage of loading assets.

DEMO VIDEO : Maybe someday there will be, but now I'm too lazy to record a video.

# Features!

  - Download any version of minecraft from early alpha, ending with the most recent versions of snapshots.
  - Asynchronous loading of assets.
  - Convenient output of the script, the result of the work will be located in the output folder.
  - In addition to any version of the client, you also get any version of the server in the kit.
  - Build on any platform, windows, linux, osx
 
 ### Todos
 
  - Asynchronous loading of libraries
  - Running all downloads parallel/asynchronously
  - Automatic assembly of the client/server launch script, along with a ready-made client distribution.
 
 ### Tech
* Python3

### Installation

Requires [python3](https://www.python.org/downloads/) to run.

### Before starting, you must specify in config, the launch platform


```sh
$ git clone https://github.com/Exordio/python-minecraft-Client-Packager
$ cd python-minecraft-Client-Packager
$ python -m venv venv 
$ venv/scripts/activate
$ pip install -r requirements.txt
$ python goldenHand.py
```
