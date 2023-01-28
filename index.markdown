---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

- Developed by <a href="https://picoluetjens.github.io">Pico Lütjens</a>
- Source Code is available <a href="https://github.com/PicoLuetjens/readme">here</a>

# General
Readme is a comand line interface tool that converts PDF to Audio. It makes use of Python and Google to read the PDF.
Right now there is only a female voice available. However most of the languages are supported. There are sometimes little 
mistakes when parsing the PDF but all in all it still works really consistent.

# Installation
**Windows:**
Otherwise readme comes as a Python script so you will need Python to run it. It can be installed from <a href="https://www.python.org/">here</a>.
Also make sure to install the Python Package Manager pip which will normaly be an option included in the Python installer.
Clone the Repository and run
```
pip install -r requirements.txt
```
If you don't want to install python on your computer, readme provides a windows installer too which will install a freeze compiled version of readme which you can then hookup to an environment variable if needed.
The installer can be downloaded here: <a href="readme-installer-windows-v-1-0.zip">readme-windows-installer-v-1-0</a>

**Linux/Mac:**
Python is in most cases already pre-installed. Make sure you have pip installed by opening a command prompt and type 
```
pip -V
```
which will print the installed pip version. If this throws an error you will need to install it.
Clone the Repository and run
```
pip install -r requirements.txt
```

# Usage
Navigate to the Repository Folder and open a command prompt. Then run the **main.py** with the parameters you want.

**Example:**
```
python main.py -i inputfile.pdf -l de -o outputfile.mp3
```

You could also add the main file as an environment variable if you like.

**Options:**
```
-i --input
```
The Inputfile(.pdf)

```
-l --language
```
The Language of the PDF File

```
-o --output
```
The Outputfile(.mp3)