# playground
An interactive Fortran playground

# Instructions to run

## Flask API server

1. Install Docker
2. Build docker image (Switch to docker directory)
```
docker build -t .
```
3. Install pipenv to manage packages 
```
pip install pipenv
```
4. Install Python dependencies
```
cd Backend
pipenv install
```
5. Run the flask server
```
pipenv run flask run
```

## React frontend

Switch to frontend folder

1. Install node packages
```
npm install
```
2. Run the server
```
npm start
```
