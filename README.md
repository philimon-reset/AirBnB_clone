# AirBnB_clone

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#Built With">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#Live Demo">Live Demo</a></li>
    <li>
      <a href="#Getting Started">Getting Started</a>
      <ul>
        <li><a href="#Prerequisites">Prerequisites</a></li>
      </ul>
      <ul>
        <li><a href="#Setup">Setup</a></li>
      </ul>
      <ul>
        <li><a href="#Usage">Usage</a></li>
      </ul>
    </li>
    <li><a href="#List of models">List of models</a></li>
    <li><a href="#Run tests">Run tests</a></li>
    <li><a href="#Authors">Authors</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
> This project is the first step towards cloning the AirBnB web app.

It includes various models and a file storage system to save instances of the models.<br />Along side this it has a custom built command line utility for quick and easy manipulation of the instances.<br />The features of the command line utility includes creating, updating, deleting, and displaying instances of any model.

## Built With

- Python 3

## Live Demo

![](https://github.com/philimon-reset/AirBnB_clone/blob/main/project.png)

## Getting Started

### Prerequisites
* Python 3+

### Setup
To startup the console:
```
python3 console.py
```

### Usage
Available commands in the console:
* `quit or EOF` to exit
* `help [model]` for help
* `create <model>` to create a new instance of a model
* `show <model> <id>` to display a specific instance based on it's model and id
* `destroy <model> <id>` to destroy a specific instance based on it's model and id
* `all [model]` displays every available instance of a model, or all models
* `update <model> <id> <attribute name> "<attribute value>"` to update a specific instance

Other methods to invoke the above commands and more:
* `<model>.all()` same as `all <model>`
* `<model>.count()` displays the number of instances of a model
* `<model>.show(<id>)` same as `show <model> <id>`
* `<model>.destroy(<id>)` same as `destroy <model> <id>`
* `<model>.update(<id>, <attribute name>, <attribute value>)` same as `update <model> <id> <attribute name> "<attribute value>"`

### List of models:
* [BaseModel](models/base_model.py)
* [User](models/user.py)
* [State](models/state.py)
* [City](models/city.py)
* [Amenity](models/amenity.py)
* [Place](models/place.py)
* [Review](models/review.py)

### Run tests
```
python3 -m unittest discover tests
```

## Authors

👤 Hizkyas Teklehaimanot

- GitHub: [@Doro-000](https://github.com/Doro-000)

👤 Philimon Derib

- GitHub: [@philimon-reset](https://github.com/philimon-reset)
