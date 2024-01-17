# Rotten Fish Production - Legends Game

This game is developed for learning purposes.
It is a simple game where you can play as a hero and fight against monsters.
The code base is used in the following talks and workshops:
- Collaborating with GitHub
- Introduction to software testing for Developers

## Install the project

Download the code via the git repository, or fork it.

Make sure you have Java 21 up and running. You can install this via JDK man or Chocolatey.
We are using OpenJDK 21.

```bash
sdk install java 21-open
sdk use java 21-open
```

Next, start up the docker containers for testing purposes.

```bash
docker-compose up -d
```

We are using the `-d` flag to run the containers in the background.

Now you can run the tests and code at will.

## Start the game

## Stop the game

## Quit the system

Run the following command to stop the docker containers.

```bash
docker-compose down -v
```

We are using the `-v` flag to remove the volumes as well.