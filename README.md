Dockerize React-App

Step1
git clone https://github.com/harshit0571/team-portfolio-dockerized

step2
cd team-portfolio-dockerized

step3

#create docker image

docker build -t harshit0571/portfolio .

step4
#run it on server
docker run -p 3000:3000 harshit0571/portfolio
