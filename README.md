# Inventory Management Python

Inventory and point-of-sale study app with Python, Tkinter and MySQL.

PT-BR: sistema simples de estoque e venda, mantido como estudo de aplicacao desktop com banco relacional.

## Overview

This project demonstrates a small desktop workflow for product lookup, sales calculation and inventory updates backed by MySQL.

## Stack

- Python
- Tkinter
- MySQL
- HTML/Bootstrap auxiliary files

## Architecture

- `main.py` contains the main sales and lookup interface.
- `add_to_db.py` handles product registration.
- `update.py` handles inventory updates.
- `web/` contains auxiliary interface assets.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install mysql-connector-python
```

Create the expected MySQL database and review connection settings in the Python files before running the app.

## Usage

```bash
python main.py
```

## Project Status

`study`

This is a supporting project for desktop UI, CRUD workflows and relational database practice.

## Roadmap

- Move database configuration to environment variables.
- Add schema creation script.
- Add screenshots of the desktop workflow.
