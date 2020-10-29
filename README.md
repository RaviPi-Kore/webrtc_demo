# Prerequisites 

The installation will require a ngrock and simple webserver like nginx, apache etc..


### Local Setup
* Please clone the code into your local machine, If you have the python running in your local you can run below command to start the server
 ```sh
python -m SimpleHTTPServer 8000  //8000 is port
```
* Run above command in the application directory.

* If you don't have the paython you can use nginx or apache server to.

* Once you deploy the code please use ngrock to get https url.
```sh
./ngrock http 8000
```
* Now you can access the application with your <ngrockurl>/index.html




