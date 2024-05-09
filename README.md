# AngularApp

This project was generated with Angular CLI version 17.3.6.
You can view this project online at: https://angular-tour-of-heroes-3f203.web.app/dashboard


## Table of Contents
### Introduction
### Structure
### Technologies used
### Usability


## Introduction

This SPA lists a custom list of heroes. It was created using Angular and through various features, heroes can be added, modified and deleted.


## Structure

The project structure is governed by the classic angular structure.
It is made up of the various components that perform the various functions.

The following used components can be found in the src/app folder:
-Dashboard
-Hero-detail
-Hero-search
-Heros
-Messages
-NotFound

Below you can find:
-App-routing
-App-component
-App.module.server
-App-module
-Hero.service
-Hero.ts
-In-memory-data.service
-Message.service
-Mock.heroes




## Tecnology used


I used several technologies to create this AngularApp:

Visual Studio Code, as editor for writing the code.
Angular to add the various features.
HTML for structure.
Typescript for the various added features.
Css to add a touch of personal class.

This app mimics communication with a remote data server by using the In-memory Web API module.
The application makes requests to and receive responses from the . The application doesn't know that the In-memory Web API is intercepting those requests, applying them to an in-memory data store, and returning simulated responses.HttpClient

Message.service has the function of displaying a message when HeroService successfully retrieves heroes


## Usability


On the main screen of Tour of Heroes we can view the Dashboard made up of the 4 main heroes.
The search bar allows you to search for heroes by name.
In the part below, the various messages deriving from the use of the functions are displayed.

By pressing the "Heroes" button you will have a list of heroes present. In this screen we can delete a hero through the "x" or add a new one through the input field.
To view a hero in detail, just click on it.
This way you will be able to have additional information and also a field to change the name.
