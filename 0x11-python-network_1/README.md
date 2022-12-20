# Network 1
Project on the following:
## General :house:
* How to fetch internet resources with the Python package urllib
* How to decode urllib body response
* How to use the Python package requests #requestsiswaysimplerthanurllib
* How to make HTTP GET request
* How to make HTTP POST/PUT/etc. request
* How to fetch JSON resources
* How to manipulate data from an external service

## Requirements :page_with_curl:
* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/python3
* A README.md file at the root of the repo, containing a description of the repository
* A README.md file, at the root of the folder of this project, is mandatory
* Your code should use the pycodestyle (version 2.8.*)
* All your files must be executable
* The length of your files will be tested using wc
* All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* You must use get to access to dictionary value by key (it won’t throw an exception if the key doesn’t exist in the dictionary)
* A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
* Your code should not be executed when imported (by using if __name__ == "__main__":)

## Tasks :heavy_check_mark:
---

### [0. What's my status? #0](./0-hbtn_status.py)
* Write a Python script that fetches https://intranet.hbtn.io/status

### [1. Response header value #0](./1-hbtn_header.py)
* Write a Python script that takes in a URL, sends a request to the URL and displays the value of the X-Request-Id variable found in the header of the response.

### [2. POST an email #0](./2-post_email.py)
* Write a Python script that takes in a URL and an email, sends a POST request to the passed URL with the email as a parameter, and displays the body of the response (decoded in utf-8)

### [3. Error code #0](./3-error_code.py)
* Write a Python script that takes in a URL, sends a request to the URL and displays the body of the response (decoded in utf-8).

### [4. What's my status? #1](./4-hbtn_status.py)
* Write a Python script that fetches https://intranet.hbtn.io/status

### [5. Response header value #1](./5-hbtn_header.py)
* Write a Python script that takes in a URL, sends a request to the URL and displays the value of the variable X-Request-Id in the response header

### [6. POST an email #1](./6-post_email.py)
* Write a Python script that takes in a URL and an email address, sends a POST request to the passed URL with the email as a parameter, and finally displays the body of the response.

### [7. Error code #1](./7-error_code.py)
* Write a Python script that takes in a URL, sends a request to the URL and displays the body of the response.

### [8. Search API](./8-json_api.py)
* Write a Python script that takes in a letter and sends a POST request to http://0.0.0.0:5000/search_user with the letter as a parameter.

### [9. Star Wars API #0](./9-starwars.py)
* Write a Python script that takes in a string and sends a search request to the Star Wars API

### [10. My Github!](./10-my_github.py)
* Write a Python script that takes your Github credentials (username and password) and uses the Github API to display your id


---
