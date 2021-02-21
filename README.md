
## Clone the repository 
_1_. git clone https://github.com/niazhussain/pyindocker.git
## How to Build Docker image
_2_. cd pyindocker/

_3_.  Run the command as `docker build -t your_desired_name_for_image .`  for example  `docker build -t myapp .`
## How to run Container
_4_.  Run the command as `docker run -d -p hostport:5000 your_desired_name_for_image` for example `docker run -d -p 8080:5000 myapp`
## Test container/ app
_5_.  Browse in your favourite browser as `http://localhost:8080/`
