# Task List App

## Overview

This is a simple Task List application built as part of a Udemy course. The app allows users to manage tasks, mark them as completed, and keep track of their progress.

## Features

- Create, read, update, and delete tasks
- Mark tasks as completed or incomplete
- Simple and clean UI
- Built with modern web technologies

## Tech Stack

- **Laravel** - Main framework for backend and business logic
- **Docker Compose** - Containerized development environment
- **Tailwind CSS** - Styling and layout
- **Alpine.js** - Used minimally for interactive UI elements

## Installation

### Prerequisites

- Docker & Docker Compose for database & db client
- PHP ^8.2 installed on your machine (or with docker)
- Composer installed on your machine (or with docker)

### Steps

1. Clone this repository:
   ```sh
   git clone git@github.com:{github_username}/task-list.git
   cd task-list
   ```
2. Copy the environment file:
   ```sh
   cp .env.example .env
   ```
3. Start the database server using Docker Compose:
   ```sh
   docker-compose up -d
   ```
4. Run Laravel migrations and seed database (if needed):
   ```sh
   php artisan migrate --seed
   ```

## Usage

- Add new tasks through the UI
- Mark tasks as completed/incomplete
- Delete tasks when no longer needed

## Development

To start a development environment:

```sh
   php artisan serve
```
