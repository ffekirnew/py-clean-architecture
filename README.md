# py-clean-architecture

This is a template repository that implements the clean architecture pattern.
If I had to come up with another name, I would have definitely called it Clean Architecture + FastAPI + MongoDB.
Because I believe those are the most important parts of this project.

## Objective

Upon going through this code, you will be able to:

- Scaffold a working clean architecture project
- Understand how to:
  - Use the dataclasses package
  - Create interfaces in python (sort of...)
  - Implement the repository & unit of work patterns
  - Create & Use generic classes in python
  - Validate data with the Pydantic package
  - And finally, appreciate types in Python.

## What you need to know / Disclaimer of Technologies used but might not be explicitly explained

### Poetry

First things first, I am using poetry for managing the packages in this project. I believe poetry makes working with
and managing python packages easily. Since it's not the topic in discussion and since there's an awesome
documentation on how to use it, it will not be discussed here today. (For more information, you can check it out at: https://python-poetry.org/)

### Clean Architecture

The clean architecture is one of the most talked about software architectures these days, and rightfully so. In my opinion, for one to truly
understand the need for the clean architecture, one needs to have suffered with other architecrues.

### FastAPI

FastAPI is one of the newest frameworks. FastAPI has lots of great features but the reason I picked it for this project is: it is simple
enough so as not to hinder our abilities to learn how the presentation layer of the architecture is going to work, but also robust enough to let us do
everything we want to do. My favorite FastAPI features include its integration with Pydantic to give us sort of the staticly typed language
experience and the readily available swagger documentation it provides.

### MongoDB

I picked MongoDB for this project because I believe it is one of the most popular NoSQL databases out there. Also, I believe it is
one of the easiest NoSQL databases to get started with, and its simplicity is something that will help us focus on the architecture
instead of the database.

### Types

I am a big fan of types. I believe they make the code more readable and easier to understand. I also believe they help us avoid
unnecessary bugs. And lastly, I believe they help us with refactoring.

## How to use this repository

This repository is a template repository. You can use it to create a new repository and start your own project.

### Prerequisites

- python 3.8
- poetry
- docker

### Setup

- Clone this repository
- Create a virtual environment
- Install the packages
- Start the docker containers
