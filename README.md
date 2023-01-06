# Termux JS
The latest version is `0.1.0`.


## How to install
The official supported version of Termux is `0.099` or later.

Download the app in .apk. Also download the [main.sh]() in files branch.

Start the app. Click on open file.

Then, select the downloaded main.sh.

Launch Termux, execute
```bash
apt upgrade && apt update
pkg install termuxplugin
termuxplugin run -C -A -F main.sh -J "your js file path here"
```
