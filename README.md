# E6156 - Topics in SW Engineering: Cloud Computing<br>First Example Microservice

## Local Project Execution

### Setup

- The first step for local project execution is to create a [virtual environment](https://docs.python.org/3/library/venv.html).
This is a best practice for developing, testing and running multiple Python applications
on a single system. There are many [explanatiosn online](https://realpython.com/python-virtual-environments-a-primer/)
for the benefits of virtual environments.


- There are several approaches to creating a venv. I recommend setting up the environment
using [PyCharm's built in wizard/tools.](https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html)


- Activate the virtual environment. You can do this in PyCharm by opening a terminal window inside
PyCharm. There should be a terminal tab at the bottom of the PyCharm window.


- In the terminal, type ```pip install -r requirements.txt``` This will install the necessary
Python packages.

  
- You can now execute the application by using the ```run``` feature in PyCharm or directly
from the terminal prompt line by typing ```python main.py```


- You will see an initialization (logging) messages followed by the message
```
 Uvicorn running on http://0.0.0.0:8012 (Press CTRL+C to quit)
```


### Execution

- Click on ```http://0.0.0.0:8012``` link to open in the browser. You can also copy and past the link.

- Accessing the URL ```http://0.0.0.0:8012/docs``` will navigate to the [OpenAPI](https://www.openapis.org/)
page/documentation for the application.








- You have completed the first part of the initial assignment.




