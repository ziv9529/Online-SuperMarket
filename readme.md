# Project Title

Online SuperMarket

## Description

On my site, you can register and order some supermarket products.<br>
As admin you can also edit your products in the store.<br><br>
Technologies I used in this project: Angular, Node.JS, MySQL, Docker.

## Images

<img src="./apps/images/shopping_1.png" width="400" height="220"> <img src="./apps/images/shopping_2.png" width="400" height="220">

<!-- ![Alt text](./apps/images/shopping_1.png?raw=true ) -->
<!-- ![Alt text](./apps/images/shopping_2.png?raw=true ) -->



## Getting Started

### Dependencies

* NodeJS, Docker

### Installing

git clone my reposetory to your local folder.

### Executing program

* open the terminal and run the following commands:
```
cd dev-apps
docker compose up
```
* open new terminal and run the following commands:
```
cd apps\server
npm install
npm run all-slim
```
* open new terminal and run the following commands:
```
cd apps\client
npm install
npm start
```

## Help

If you running into a docker problem, check if the port 3306 of MySQL is available,
```
docker compose down 
```
after you make sure the port is available, run the following command in the dev-apps folder: 
```
docker compose up 
```

## Authors

Ziv Ashkenazi 
[@Linkdin](https://www.linkedin.com/in/ziv-ashkenazi/)
