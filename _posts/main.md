---
layout: post
title: CS 3420 Final Project - PONG
# subtitle: Each post also has a subtitle
gh-repo: emerisly/embedded_final_project
# gh-badge: [star, fork, follow]
# tags: [test]
# comments: true
---

## Introduction

We present a game called "Pong" that is designed to be played using a FRDM-K64F board connected to a local computer via a USB cable. The game interface, developed using Python, includes a graphical user interface (GUI) with a ball and a bar displayed on the computer screen. The ball moves around the screen, bouncing up and down, while simulating a basic physics engine with collisions. The FRDM-K64F board serves as the game controller, and players must use it to control the bar's movement and keep the ball bouncing by shaking the board in the desired direction. Each successful bounce earns the player one point, and the objective is to maintain the ball's movement for as long as possible. However, if the bar fails to catch the ball, causing it to fall below the bar, the game ends. Overall, our game "Pong" offers an engaging and challenging experience for players of all ages.


## System Overview
Our system comprises of two main components: the game logic and the controller logic. The game logic is written in PyGame and will run on a local computer, while the controller logic is a C program that will run on the FRDM-KL46Z board. The two components will be connected via a Universal Serial Bus (USB) cable, which will also provide power to the board.
As a peripheral control for the game, the board, equipped with an accelerometer, will continuously read data from the accelerometer and send it to the laptop computer. The computer will interpret the data and trigger the corresponding action in the game. To achieve this, we plan to use a periodic real-time process that operates at a fixed interval, enabling us to monitor the board's movements and use it to control the game effectively.
Overall, our system is designed to provide an engaging and interactive gaming experience, with the FRDM-KL46Z board acting as a reliable and responsive controller for the game.

[rest work in progress]

## Video Demo


## Technical Description


## Testing Scheme


## Additional Resources Used
