# BEW 2.2: Challenge 3 - Dockerize Any Flask App

## Description

The goal of this challenge is to dockerize any Flask application.

The app I've chosen is [E-ZParse](https://github.com/shah-a/int1.3-e-zparse)

Note: The purpose of this repo is just to practice writing Dockerfiles. Therefore, the full fileset of E-ZParse is not present here (i.e. docs and other miscellaneous files). Additionally, future updates to E-ZParse will not be reflected here.

## Usage

```bash
docker build . -t e-zparse
docker run -d -p 5000:5000 e-zparse
```
