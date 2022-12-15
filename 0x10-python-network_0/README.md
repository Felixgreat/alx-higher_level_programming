# Network 0
This Project focus on the following:

## General :house:
* What a URL is
* What HTTP is
* How to read a URL
* The scheme for a HTTP URL
* What a domain name is
* What a sub-domain is
* How to define a port number in a URL
* What a query string is
* What an HTTP request is
* What an HTTP response is
* What HTTP headers are
* What the HTTP message body is
* What an HTTP request method is
* What an HTTP response status code is
* What an HTTP Cookie is
* How to make a request with cURL
* What happens when you type google.com in your browser (**Application level**)

## Requirements :page_with_curl:
* Allowed editors: vi, vim, emacs
* - A README.md file, at the root of the folder of the project, is mandatory
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your Bash scripts should be exactly 3 lines long (wc -l file should print 3)
* All your files should end with a new line
* All your files must be executable
* The first line of all your bash files should be exactly #!/bin/bash
* The second line of all your Bash scripts should be a comment explaining what is the script doing
* All curl commands must have the option -s (silent mode)
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* The first line of all your Python files should be exactly #!/usr/bin/python3
* Your code should use the pycodestyle (version 2.8.*)
* All your modules should be documented: python3 -c 'print(__import__("my_module").__doc__)'
* All your classes should be documented: python3 -c 'print(__import__("my_module").MyClass.__doc__)'
* All your functions (inside and outside a class) should be documented: python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
* A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

## Tasks :heavy_check_mark:
| Filename | Functions |
| ----------- | ----------------------- |
| `0-body_size.sh` | `Write a Bash script that takes in a URL, sends a request to that URL, and displays the size of the body of the response` |
| `1-body.sh` | `Write a Bash script that takes in a URL, sends a ""GET"" request to the URL, and displays the body of the response` |
| `2-delete.sh` | `Write a Bash script that sends a DELETE request to the URL passed as the first argument and displays the body of the response` |
| `3-methods.sh` | `Write a Bash script that takes in a URL and displays all HTTP methods the server will accept.` |
| `4-header.sh` | `Write a Bash script that takes in a URL as an argument, sends a ""GET"" request to the URL, and displays the body of the response` |
| `5-post_params.sh` | `Write a Bash script that takes in a URL, sends a ""POST"" request to the passed URL, and displays the body of the response` |
| `6-peak.py` | `Write a function that finds a peak in a list of unsorted integers. `Prototype: def find_peak(list_of_integers):` ` |
| `6-peak.txt` | `must contain the complexity of your algorithm: O(log(n)), O(n), O(nlog(n)) or O(n2)` |
| `100-status_code.sh` | `Write a Bash script that sends a request to a URL passed as an argument, and displays only the status code of the response.` |
| `101-post_json.sh` | `Write a Bash script that sends a JSON ""POST"" request to a URL passed as the first argument, and displays the body of the response.` |
| `102-catch_me.sh` | `Write a Bash script that makes a request to ""0.0.0.0:5000/catch_me"" that causes the server to respond with a message containing ""You got me!,"" in the body of the response.` |
