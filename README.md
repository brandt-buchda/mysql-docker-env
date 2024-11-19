# Setup Instructions

## Step 1 - Enable Version Control System
In the top menu, go to `Git` -> `Enable Version Control Integration`

Alternatively, on macOS press `^Ctr` `V` and select `Enable Version Control Integration`

## Step 2 - Create a new project from GitHub
In the top menu, go to `Git` -> `Clone`. Paste the following link in the `URL` section and click `Clone`,

```
https://github.com/brandt-buchda/mysql-docker-env.git
```

At this point, DataGrip should clone this repository and create a new project for you with a single MySQL datasource at localhost:3307

## Step 3 - Create the MySQL Server
Open a termial in the project directory and run the following command. Make sure Docker Destop is up and running.


```shell
docker-compose up
```

## Step 4 - Connect to the Server
Once docker completes and server is running, connect to the datasource:

| Setting  | Value     |
|----------|-----------|
| Host     | localhost |
| Port     | 3307      |
| User     | root      |
| Password | rootroot  |

