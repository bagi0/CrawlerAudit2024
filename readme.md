# CrawlerAudit Docker Image

## Written by Rashad Baghiyev

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage Guide](#usage-guide)

## Project Overview
CrawlerAudit is a simple Dockerized PHP application designed to test and evaluate the capabilities of web crawling tools and vulnerability scanners. This application simulates a multi-tier web environment embedded with various interactive elements to challenge and assess the robustness and thoroughness of scanning tools in efficiently mapping web structures. There are 5000 pages that can be crawled.

## Features
- **Web Page Structure**: Implements a layered structure of web pages with varying complexity to mimic realistic internet environments.
- **Interactive Elements**: Includes forms, buttons, links, and dynamic content to test interaction handling by crawlers.
- **Performance Metrics**: Provides analytics on crawler performance, only about speed and coverage.

## Getting Started
Follow these detailed steps to get a copy of CrawlerAudit running on your local machine for development and testing purposes.

### Prerequisites
- **Docker**: Ensure Docker is installed on your system. Visit [Docker's official site]([[https://www.docker.com/get-started](https://hub.docker.com/r/rashad8888/crawleraudit)](https://hub.docker.com/r/rashad8888/crawleraudit)) for installation instructions.

### Installation
1. **Pull the Docker Image**
   ```bash
   docker pull rashad8888/crawleraudit:latest
   docker run -d -p 80:80 rashad8888/crawleraudit:latest
   
### Usage Guide
 After installing and running the Docker container as described above, you can start using the application:
Access the Application: Open your browser and go to http://localhost. You will be greeted by the CrawlerAudit interface.

Manual link to access the project
https://hub.docker.com/r/rashad8888/crawleraudit
