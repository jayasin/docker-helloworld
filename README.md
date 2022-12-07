## Hello World - Using Docker

* Clone the Project   `git clone https://github.com/jayasin/docker-helloworld.git`
* change the working directory `cd docker-helloworld.git`
* build the container `docker build -t landingpage .`
* Run the container `docker run -dp 80:80 landingpage`
* visit `http://localhost` to view the static webpage in your browser

To **stop** all containers - `docker stop $(docker ps -a -q)`
To **remove** all containers - `docker rm $(docker ps -a -q)`
Edit the `index.html` file as per your requirement and do the steps 2 & 3 (don't forget to stop and remove previous container)

<Happy Coding/>
Thanks & Regards, 
`Jayasin Prabhu C` - https://github.com/jayasin