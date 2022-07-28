# Microservice 
This microservice is apart of Assignment 7 for CS361. 

## What this project does:
This microservice creates an API that will take in someones birthday in the form {month}{day} in numbers and return their astrological sign. 

## How to use the microservice:

1. Open your terminal and clone this repository on your local hardrive. 
```
    git clone {link to repository ssh or https}
```
2. Navigate into the cloned repository. 
```
    cd Project-CS361
```
3. Visit the  [this page](https://fastapi.tiangolo.com/contributing/) to create and activate a virutal environment in which the microservice will run. 
```
    python -m venv env
    source ./env/bin/activate
```
4. Visit the  [this page](https://fastapi.tiangolo.com/tutorial/#install-fastapi) to install the FastAPI Python library.  
```
    pip install "fastapi[all]"
```
3. Run main.py
```
    python main.py 
```

## Using the API
Once you have run main.py you should see this in your terminal: 

![main.py running in terminal](/images/main.png)

Copy this into your browser:

![main.py running in terminal](/images/url.png)

This should appear:

![main.py running in terminal](/images/sign.png)

Type "/generate/{month}{day}" after the url inserting your month in number format. It should look like this:

![main.py running in terminal](/images/date.png)

If you have done everything right, the API should return your sign:

![main.py running in terminal](/images/return.png)

## UML Diagram

![UML](/images/uml.png)





