---
title: "Calibration Tool"
description: "Marking free objects on a map for anyone to pick up"
date: "2022-09-24"
---


## Project sumary
The calibration tool is used to calibrate surgical lights to have the same birghtness on different levels.
A requirement was that it should be a windows desktop app that still uses angular.io for the frontend.
It was solved by using .NET MAUI with a webview that displays an angular.io app. 
The frontend is hosted on a different thread as an asp.net core server.
Communication between the frontend and backend is done via a WebPushApi. 
The backend communicates with the surgical light controler via a CAN-open bus.

## Tech Stack 
* .NET MAUI
* angular.io
* asp.net core
* CAN-open Bus
