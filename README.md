# How to Build and Run a Team Portfolio App using React and Docker

## Pre-requisite

- React
- Docker Desktop

## Getting Started

## Step1 - Clone the repository

```
git clone https://github.com/harshit0571/team-portfolio-dockerized
```

## Step2 - Change directory 

```
cd team-portfolio-dockerized
```

## Step3 : Building the Docker Image



```
docker build -t harshit0571/portfolio .
```

## Step4 - Running the App


```
docker run -p 3000:3000 harshit0571/portfolio
```

<img width="1214" alt="image" src="https://user-images.githubusercontent.com/34368930/183401129-3bd7b384-7d86-4f7b-8442-791cb2bbb89b.png">
