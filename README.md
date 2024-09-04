# Flappy_AI

Overview

This project is an AI-based Flappy Bird simulation that uses a genetic algorithm to train a population of birds to play the game. The project is built using the p5.js library and demonstrates the process of evolution as the birds improve their performance over generations.
Features

    Flappy Bird Simulation: A simplified version of the Flappy Bird game where multiple birds attempt to fly through obstacles.
    Genetic Algorithm: The birds learn over time using a genetic algorithm, which evolves the population by selecting the best-performing birds and generating offspring.
    Real-Time Visualization: The simulation is visualized in real-time, with information about the current score, high score, generation, and the number of birds still alive.
    Adjustable Simulation Speed: Users can control the speed of the simulation with different preset speeds.

Project Structure

    index.html: The main HTML file that sets up the environment, includes the required scripts, and loads the game.
    style.css: Contains the styles used for the visualizer interface.
    sketch.js: The main script that initializes the canvas, manages the game loop, and handles the genetic algorithm.
    source/: Contains individual JavaScript files for different game components:
        bird.js: Defines the Bird class, which represents each bird in the game.
        level.js: Manages the game level, including the pipes and the environment.
        pipe.js: Handles the logic for the pipes that the birds must navigate through.
        button.js: Implements the buttons used to control the simulation speed.
        smartbird.js: Extends the Bird class with neural network capabilities to make decisions.
    lib/: Contains libraries used for AI:
        nn.js: Implements a simple neural network.
        matrix.js: Provides matrix operations required for the neural network.

Getting Started
Prerequisites

    A modern web browser with JavaScript enabled.
    Basic understanding of HTML, JavaScript, and the p5.js library.

Installation

    Clone the repository:

    bash

    git clone <repository-url>
    cd flappy-bird-ai

    Open the index.html file:
        Simply open the index.html file in your preferred web browser to start the simulation.

Usage

    Start the Simulation: The simulation begins automatically when the page is loaded.
    Control Speed: Use the buttons at the bottom of the screen to adjust the simulation speed.
        Options include 1x, 2x, 10x, and MAX speed.
    Observe Evolution: Watch as the birds evolve over generations, gradually improving their ability to navigate through the pipes.

https://github.com/user-attachments/assets/bf6bd5a7-42d6-4da1-8b09-86f171622ddf

