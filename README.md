# DRINKS

This is a simple project created to learn to use Django Rest Framework to create an API that can be consumed by any frontend. Need to learn to implement associations as this project on includes one model.

In terms of sparating concerns, instead of one views file, we can have a views directory with many modules that handle their own tasks. Then have a file name '\__init__.py' that will have all the modules imported in it and acts as the entry point of the directory thus one can keep their paths in the urls.py file asthey would normally have it. Find more info [here](https://simpleisbetterthancomplex.com/tutorial/2016/08/02/how-to-split-views-into-multiple-files.html)

## Project Setup

- Open a terminal / command line interface on your computer​

- Clone the repo into your folder of choice by using the following:​​git clone https://github.com/Malcolm-G/charity-app​

- Change directory to the repo folder:​​cd charity-app

- (Optional) Open it in Visual Studio Code​

  code .

- (Alternate Option) Open it in any editor of your choice.​

- Create a virtual environment by running
    ```
    python3 -m venv venv
    ```
- Activate the virtual environment:
  ```
  . ./venv/bin/activate
  ```
- Install project dependencies:
  ```
  pip install -r requirements.txt
  ```

  ## Extra Info
  You can find more info on the requirements.txt [here](https://dev.to/voilalex/automatically-manage-python-dependencies-with-requirementstxt-5g11)