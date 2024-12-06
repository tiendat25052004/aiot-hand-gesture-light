# AIoT Hand Gesture Light Control

A smart light control system using AIoT technology, enabling users to turn lights on and off through hand gestures. This project combines computer vision and IoT for seamless gesture-based interaction.

## Table of Contents

- [AIoT Hand Gesture Light Control](#aiot-hand-gesture-light-control)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)

## Introduction

This project leverages AI and IoT technologies to create a smart light control system. Users can control lights using hand gestures, making it a convenient and modern solution for home automation.

## Features

- Hand gesture recognition using computer vision
- Real-time light control
- Easy setup and configuration
- Supports multiple gestures

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/tiendat25052004/aiot-hand-gesture-light.git
    cd aiot-hand-gesture-light
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Download the necessary data files (or create your data with mediapy):
    ```sh
    !gdown 1gzWOtABiVmJ38usCSDe5F9gR2tECt3zu -O data/
    !gdown 1nIo1_wBmkovz-u_BCsV5c1Kbz6ZqoKwq -O data/
    !gdown 1ZteHYSgbuZu_GcUJHW8ZzoZv1DE8-oLw -O data/
    ```

## Usage

1. Prepare the dataset:
    ```sh
    python src/data_preprocessing/generate_landmark_data.py
    ```

2. Train the model:
    ```sh
    jupyter notebook notebooks/train_model.ipynb
    ```

3. Run the main application:
    ```sh
    python main.py
    ```

## Project Structure