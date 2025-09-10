# Hello World Static Website

## Overview
This is a simple static HTML project containing a single "Hello World" page. The project has been successfully configured to run in the Replit environment.

## Project Structure
- `hello-world.html` - Main HTML file with a simple "Hello World" message in Japanese

## Configuration
- **Language**: HTML (static web content)
- **Web Server**: Python's built-in HTTP server
- **Port**: 5000 (configured for Replit environment)
- **Host**: 0.0.0.0 (allows external access through Replit's proxy)

## Deployment
- **Target**: Autoscale (suitable for static websites)
- **Command**: `python3 -m http.server 5000 --bind 0.0.0.0`

## Setup Date
- Configured: September 10, 2025
- Status: Working and ready for use

## Usage
The website is accessible through Replit's web preview. The server serves the HTML file and can handle multiple concurrent requests through the autoscale deployment configuration.