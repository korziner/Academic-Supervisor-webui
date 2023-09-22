# Academic-Supervisor Web UI

Welcome to Academic-Supervisor WebUI (Academic-Supervisor: One tool to rule them all), the hub for LLM (Large Language Model) models. This project aims to provide a user-friendly interface to access and utilize various LLM models for a wide range of tasks. Whether you need help with writing, coding, organizing data, generating images, generating music or seeking answers to your questions, Academic-Supervisor WebUI has got you covered.

As an all-encompassing tool with access to over 300 AI expert conditionning across diverse domains and more than 500 fine tuned models over multiple domains, you now have an immediate resource for any problem. Whether your genomic pipeline needs repair or if you need coding assistance in Python, C++ or JavaScript; 

feeling down about life decisions that were made wrongly yet unable see how? Ask Academic-Supervisor. 

Need guidance on what lies ahead healthwise based on current symptoms presented, our medical assistance AI can help you get a potential diagnosis and guide you to seek the right medical care. 

If stuck with legal matters such contract interpretation feel free reach out to Lawyer personality, to get some insight at hand -all without leaving comfort home. 

Not only does it aid students struggling through those lengthy lectors but provides them extra support during assessments too, so they are able grasp concepts properly rather then just reading along lines which could leave many confused afterward. 

Need illustration work done? No worries, Artbot got us covered there! And last but definitely not least LordOfMusic here for music generation according to individual specifications. So essentially say goodbye boring nights alone because everything possible can be achieved within one single platform called Academic-Supervisor...

## Features

- Choose your preferred binding, model, and personality for your tasks
- Enhance your emails, essays, code debugging, thought organization, and more
- Explore a wide range of functionalities, such as searching, data organization, image generation, and music generation
- Easy-to-use UI with light and dark mode options
- Integration with GitHub repository for easy access
- Support for different personalities with predefined welcome messages
- Thumb up/down rating for generated answers
- Copy, edit, and remove messages
- Local database storage for your discussions
- Search, export, and delete multiple discussions
- Support for image/video generation based on stable diffusion
- Support for music generation based on musicgen
- Support for multi generation peer to peer network through Academic-Supervisor Nodes and Petals.
- Support for Docker, conda, and manual virtual environment setups


Thank you for all users who tested this tool and helped making it more user friendly.

## Installation
### Automatic installation (UI)
If you are using Windows, just visit the release page, download the windows installer and install it.

### Automatic installation (Console)
Download the installation script from scripts folder and run it.
The installation scripts are:
- `win_install.bat` for Windows.
- `linux_install.sh`for Linux.
- `mac_install.sh`for Mac.

### Manual install with Anaconda/Miniconda:
If you don't have anaconda or miniconda installed, please install it:
[Install miniconda](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html)
Make sure to add it to your path so that you can run it easily from a terminal.
If you don't have git installed, please install it:
[Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
Make sure to add it to your path so that you can run it easily from a terminal.
- Run a terminal and create a new environment called `Academic-Supervisor` with python 3.10:
```bash
conda create --name Academic-Supervisor python=3.10
```
- Activate the environment
```bash
conda activate Academic-Supervisor
```
- Clone the project
```bash
git clone https://github.com/korziner/Academic-Supervisor-webui.git
```
- enter the Academic-Supervisor-webui folder
```bash
cd Academic-Supervisor-webui
```
- install dependancies
```bash
pip install --upgrade -r requirements.txt
```
- run the application
```bash
python app.py
```
### Manual install with virtual env:
Make sure you install python 3.10, and git:
[Install python](https://www.python.org/downloads/release/python-31013/)
Make sure to add it to your path so that you can run it easily from a terminal.
If you don't have git installed, please install it:
[Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
Make sure to add it to your path so that you can run it easily from a terminal.
- Run a terminal and install pip:
```bash
python -m ensurepip --upgrade
```
- Install virtual environment:
```bash
pip install venv
```
- Clone the project
```bash
git clone https://github.com/korziner/Academic-Supervisor-webui.git
```
- enter the Academic-Supervisor-webui folder
```bash
cd Academic-Supervisor-webui
```
- Create a virtual environment
```bash
python -m venv ./env
```
- Activate the virtual environment:
- On windows: `./env/Scripts/activate`
- On linux: `./env/bin/activate`
- On macos: `./env/bin/activate`
- install dependancies
```bash
pip install --upgrade -r requirements.txt
```
- run the application
```bash
python app.py
```

Once installed, you need to activate the environment then run the app.

# Code of conduct

By using this tool, users agree to follow these guidelines :
- This tool is not meant to be used for building and spreading fakenews / misinformation.
- You are responsible for what you generate by using this tool. The creators will take no responsibility for anything created via this Academic-Supervisor.
- You can use Academic-Supervisor in your own project free of charge if you agree to respect the Apache 2.0 licenseterms. Please refer to https://www.apache.org/licenses/LICENSE-2.0 .
- You are not allowed to use Academic-Supervisor to harm others directly or indirectly. This tool is meant for peacefull purposes and should be used for good never for bad.
- Users must comply with local laws when accessing content provided by third parties like OpenAI API etc., including copyright restrictions where applicable.

# Disclaimer
Large Language Models are amazing tools that can be used for diverse purposes. Academic-Supervisor was built to harness this power to help the user inhance its productivity. But you need to keep in mind that these models have their limitations and should not replace human intelligence or creativity, but rather augment it by providing suggestions based on patterns found within large amounts of data. It is up to each individual how they choose use them responsibly!

The performance of the system varies depending on the used model, its size and the dataset on whichit has been trained. The larger a language model's training set (the more examples), generally speaking - better results will follow when using such systems as opposed those with smaller ones. But there is still no garantee that the output generated from any given prompt would always be perfect and it may contain errors due various reasons. So please make sure you do not use it for serious matters like choosing medications or making financial decisions without consultating an expert first hand ! 

# license
This repository uses code under ApacheLicense Version 2.0 , see [license](https://github.com/korziner/Academic-Supervisor-webui/blob/main/LICENSE) file for details about rights granted with respect to usage & distribution

# Copyright:
ParisNeo 2023


