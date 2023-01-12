# Imageconversion_FastAPI
To install the project: 
    1)Clone the project from github
    2)Create and activate Virtual Environment 
    3)Install the dependencies from dependencies.txt
    4)create a file name .env and set the following environment variables
        
        SECRET_KEY = " " -> Generate the SECRET_KEY 
        ALGORITHM = "HS256"
        POSTGRES_USER=
        POSTGRES_PASSWORD=
        POSTGRES_SERVER=
        POSTGRES_DB=

        TEST_POSTGRES_DB=  (separate database to run unittest)<br />
        
    5)Command to run the project-> uvicorn main:app --reload <br />
    6)Go to /docs for all the routes <br />
    7)Command to run the test -> python -m pytest <br />
