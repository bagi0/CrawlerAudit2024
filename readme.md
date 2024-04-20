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
CrawlerAudit is a comprehensive Dockerized PHP application designed to test and evaluate the capabilities of web crawling tools and vulnerability scanners. This application simulates a multi-tier web environment embedded with various interactive elements to challenge and assess the robustness and thoroughness of scanning tools in identifying potential vulnerabilities and efficiently mapping web structures.

## Features
- **Complex Web Page Structure**: Implements a layered structure of web pages with varying complexity to mimic realistic internet environments.
- **Interactive Elements**: Includes forms, buttons, links, and dynamic content to test interaction handling by crawlers.
- **Customizable Settings**: Users can adjust settings to simulate different environments and conditions.
- **Performance Metrics**: Provides analytics on crawler performance, including speed, accuracy, and coverage.

## Getting Started
Follow these detailed steps to get a copy of CrawlerAudit running on your local machine for development and testing purposes.

### Prerequisites
- **Docker**: Ensure Docker is installed on your system. Visit [Docker's official site](https://www.docker.com/get-started) for installation instructions.

### Installation
1. **Pull the Docker Image**
   ```bash
   docker pull rashad8888/crawleraudit:latest
   docker run -d -p 8080:80 rashad8888/crawleraudit:latest
   
### Usage Guide
 After installing and running the Docker container as described above, you can start using the application:
Access the Application: Open your browser and go to http://localhost:8080. You will be greeted by the CrawlerAudit interface.

