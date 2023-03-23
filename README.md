# fallparams
Using this tool you can find the name and ID attributes
in `<a>` and `<input>` tags

#Installation
* required python3.6 > , pip3

Download your Chrome driver (linux / windows / mac) from this 
[ Link ](https://chromedriver.storage.googleapis.com/index.html?path=100.0.4896.60/)
in the project list and decompress it.

if selenium web driver is not installed on you server, install it with this Link:
[ Link ](https://tecadmin.net/setup-selenium-chromedriver-on-ubuntu/)

# How to configure python3 package requirements
1. In the project root directory, run the following command:
- `python3 -m venv .venv`
2. Activate the virtual environment:
- `source .venv/bin/activate`
3. Install the required packages:
- `python3 -m pip install -r requirements.txt`
And Ready!

#Usage Models
1. ``python3 FallParams.py -u https://www.google.com``
2. ``echo "https://google.com" | python3 FallParams.py``
3. ``python3 FallParams.py`` and after running the program, Enter in the input

**results are store in the output/ directory**