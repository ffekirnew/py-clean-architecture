# py-clean-architecture

This is a template repository that implements the clean architecture pattern.
If I had to come up with another name, I would have definitely called it Clean Architecture + FastAPI + MongoDB.
Because I believe those are the most important parts of this project.

## Objective

Upon going through this code, you will understand how to:

- Perform dependency injection in python
- Use the dataclasses package
- Create interfaces in python (sort of...)
- Implement the repository & unit of work patterns
- Create & Use generic classes in python
- Validate data with the Pydantic package
- And finally, appreciate types in Python.

## Technologies used but may not be explicitly explained

This are technologies that I have used through out the layers of the project to demonstrate the uses of the clean architecture. I will explain some of the code I
have written with them but will not provide full details as this is an example and explanation of how I implemented the clean architecture.

### Poetry

First things first, I am using poetry for managing the packages in this project. I believe poetry makes working with
and managing python packages easily. Since it's not the topic in discussion and since there's an awesome
documentation on how to use it, it will not be discussed here today. (For more information, you can check it out at: https://python-poetry.org/)

### FastAPI

FastAPI is one of the newest frameworks. FastAPI has lots of great features but the reason I picked it for this project is: it is simple
enough so as not to hinder our abilities to learn how the presentation layer of the architecture is going to work, but also robust enough to let us do
everything we want to do. My favorite FastAPI features include its integration with Pydantic to give us sort of the staticly typed language
experience and the readily available swagger documentation it provides.

### MongoDB (and the pymongo package)

I picked MongoDB for this project because I believe it is one of the most popular NoSQL databases out there. Also, I believe it is
one of the easiest NoSQL databases to get started with, and its simplicity is something that will help us focus on the architecture
instead of the database.

### Resend

I picked resend as the service to show how third-party services can come into play. Resend is an awesome
service that allows us to send bulk emails to our recipients. It has an awesome api that allows us to send mails with literally 14 lines of code.

## How the code was written

### Domain Layer

TODO

### Application Layer

TODO

### Persistence Layer

TODO

### Infrastructure Layer

TODO

### Presentation Layer (Web API Layer)

TODO

## How to use this repository

This repository is a template repository. You can use it to create a new repository and start your own project.

### Prerequisites

- python 3.8
- poetry

### Setup

- Clone this repository

```bash
git clone https://github.com/ffekirnew/py-clean-architecture
```

- Install the packages

```bash
poetry install
```

- Spin poetry's virtual environment

```bash
poetry shell
```

- Run the application which will run `webapi/main.py`

```bash
poetry run uvicorn src.main:app --reload
```
