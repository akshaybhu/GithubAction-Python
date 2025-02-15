GitHub Actions CI/CD Pipeline Flask App



Objective:

Implement a CI/CD workflow using GitHub Actions for a Python application.


Setup

Github repository link https://github.com/akshaybhu/GithubAction-Python
Create 2 EC2 instances, 1 for prod and 1 for staging.

Install dependencies on both instances like Flask, python, pip, git, pytest.

sudo su

yum install -y python3 python3-pip
yum install git -y
pip install flask
pip install pytest

Clone git repo https://github.com/akshaybhu/GithubAction-Python

Run python using command:

Python3 app.py (staging running on port12345)

Python3 app.py (prod running on port12345)
