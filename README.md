# tic-tac-toe

> A command-line implementation of the classic Tic Tac Toe game, written in Ruby.

## About the Project

This project is a simple two-player game in which players take turns placing their symbol (X, O, etc.) on a 3x3 grid. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.

![Demo of tic-tac-toe](https://github.com/luizvilasboas/tic-tac-toe/blob/main/img/demo.png?raw=true)

## Tech Stack

*   [Ruby](https://www.ruby-lang.org/)
*   [Bundler](https://bundler.io/)
*   [Docker](https://www.docker.com/)

## Usage

You can run this project in three different ways: locally on your machine, inside a Docker container, or directly in your browser via Replit.

### Prerequisites

*   For local execution: [Ruby](https://www.ruby-lang.org) and [Bundler](https://bundler.io/)
*   For containerized execution: [Docker](https://docs.docker.com/get-docker/)

### 1. Run on Your Local Machine

1.  **Clone the repository**
    ```bash
    git clone https://github.com/luizvilasboas/tic-tac-toe.git
    ```
2.  **Navigate to the project directory**
    ```bash
    cd tic-tac-toe
    ```
3.  **Install dependencies**
    ```bash
    bundle install
    ```
4.  **Run the game**
    ```bash
    ruby lib/tic_tac_toe.rb
    ```

### 2. Run in a Docker Container

1.  **Clone the repository**
    ```bash
    git clone https://github.com/luizvilasboas/tic-tac-toe.git
    ```
2.  **Navigate to the project directory**
    ```bash
    cd tic-tac-toe
    ```
3.  **Build the Docker image**
    ```bash
    docker build -t olooeez/tic-tac-toe:latest .
    ```
4.  **Run the game in a container**
    ```bash
    docker run -it --rm olooeez/tic-tac-toe:latest
    ```

### 3. Run in Your Browser

You can play the game directly in your browser by visiting the project on Replit:
**[Play on Replit](https://replit.com/@olooeez/tic-tac-toe)**

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
