# 🏦 Online Banking System

This is an Online Banking Concept created using Django Web Framework.

## ✨ Features

✅ Create Bank Account

✅ Deposit & Withdraw Money

✅ Support for Account Types (Savings, Current, etc.)

✅ Automatic Interest Calculation (per account type)

✅ Transaction Report with Date Filter

✅ Balance Tracking after Every Transaction

✅ Scheduled Interest Calculation using Celery

✅ Min/Max Transaction Limit Restrictions

✅ Modern UI with Tailwind CSS

## 🛠️ Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, TailwindCSS

Task Queue: Celery

Database: SQLite (default, can use PostgreSQL/MySQL)

Cache & Queue Broker: Redis

## 📋 Prerequisites

#### Make sure you have installed:

Python >= 3.7

Redis Server

Git

pip

Virtualenv (virtualenvwrapper is recommended)


## ⚙️ Installation

#### Create & activate a virtual environment:
```bash 
python -m venv venv
```
#### Activate (Windows)
```bash
venv\Scripts\activate
```
#### Activate (Linux/Mac)
```bash
source venv/bin/activate
```


#### Install dependencies:
```bash
pip install -r requirements.txt
```
#### Apply migrations:
```bash
python manage.py migrate
```
#### Create an admin (superuser):
```bash
python manage.py createsuperuser
```
#### Run the development server:
```bash
python manage.py runserver
```

## 🚀 Usage

- Access the app at: http://127.0.0.1:8000

- Login as superuser to manage accounts.

- Create accounts, deposit/withdraw money, view reports.










