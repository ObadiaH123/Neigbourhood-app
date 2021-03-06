
# MY NEIGHBOURHOOD


## Author
KIPROTICH BETT BENARD



## Description
Neighbourhood project is about how people living in an area can get the necessary services easily. The fraternity can share posts which relates to them and the neighbourhood is kept updated by reading various posts. The user needs to register and select his or her neighbourhood. The user can only see the post or access the services for example the authorities only from his or her neighbourhood. The users can also change their neighbourhood at will.

## Setup and installations
* Clone Project to your machine
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.8 manage.py runserver`
* Access the live site using the local host provided


## Getting started
### Prerequisites
* python3.8
* virtual environment
* pip

#### Clone the Repo and rename it to suit your needs.
```bash
git clone https://github.com/ObadiaH123/Neigbourhood-app.git
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```
#### Create and activate the virtual environment
```bash
python3.8 -m venv virtual
```
```bash
source virtual/bin/activate

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.8 manage.py check
python manage.py makemigrations news
python3.8 manage.py sqlmigrate news 0001
python3.8 manage.py migrate
```
#### Run the app
```bash
python3.8 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000)
## Testing the Application
`python3.8 manager.py tests`
## Built With
* [Python3.6](https://docs.python.org/3/)
* Django
* Boostrap
* HTML
* CSS

 # Technologies Used
<precode>
<code>

- Python3

- Django3

- Heroku (for deployment)

- Git
<code>
<precode>
# Bugs

No known bugs at the moment



## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

