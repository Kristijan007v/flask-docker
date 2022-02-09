
# Flask-Docker Starter Template

> ## About
>This template was made to make it easier to start working with Flask and docker and to save you time. I got you covered, now start coding 👨‍💻 ☕
> ### Author
> Kristijan Vidović

> ## Folder structure
> - [**setup**](setup)
> - [**static**](static)
> - [**templates**](templates)




> ## Prerequsites
> To get started make sure you have Python 3 installed on your system (version 3.10), if not you can download it [here.](https://www.python.org/) You have to have Python PATH set if you are using Windows to be able to use "python" command. See instructions [here.](https://www.python.org/) You need to have [Docker for Windows](https://docs.docker.com/desktop/windows/install/) installed on your PC.
> ## Getting started
> To get started make sure you have Python 3 installed on your system (version 3.10), if not you can download it [here.](https://www.python.org/)
> ### Optional
> Installed [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) VS Code exstensions if you are using VS Code as you code editor.

> ## Installation and setup
> 1. **First we need to setup virtual environment** (This step is optional)\
> Type in this command to your VS Code or CMD (make sure you are in the right directory):
> ```python
> python -m venv <choose-name>
>```
>\
> Activate your virtual environment:
> ```python
> <choosen-name>\Scripts\activate.bat  or  <choosen-nam>\Scripts\activate   
>```
> 2. **Second, install all required dependencies**\
> To install all required dependencies run:
> ```python
> pip install -r requirements.txt
>```
> 3. **Build your docker image** (This step is optional)
> \
> To build your docker image type in (make sure you are in a dir where the dockerfile is located):
> ```python
> docker build -t <docker-username>/<app-name>:<app-version> .
>```
> ## Run options
> If you have done all the steps required above.\
> Now you can run your Flask application in two ways:
> 1. ### Run using Docker
> Type this command or run your image from Docker Desktop application:\
> ```python
> docker run -p 5000:5000 <image-name> #You can find your image name in your Docker Desktop app
>```
> Now you can visit [localhost:5000](http://localhost:5000) to view your Flask app
>
> 2. ### Run without Docker
> To start your Flask app you can type in this command (make sure you have activated your virtual env and that you are in the right dir):
> ```python
> python app.py
>```
> Now you can visit [127.0.0.1:5000](http://127.0.0.1:5000/) to view your Flask app
> ## Contact me
> Feel free to contact me on my personal email vidovic@kristijan.me or using the contact form on my [personal website.](https://kristijan.me) 😊