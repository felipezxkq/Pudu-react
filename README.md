![Banner](https://i.imgur.com/KDT9aot.png)


## Contents

- [Pudu](#pudu)
  - [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [Call for code 2022 video](#call-for-code-2022-video)
  - [Video Demo Hackathon LATAM](#video-demo-hackathon-latam)
  - [The architecture](#the-architecture)
  - [Project roadmap](#project-roadmap)
  - [Getting started](#getting-started)
  - [Built with](#built-with)
  - [Authors](#authors)
  - [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

Food production greenhouse emissions is one of the most important causes of climate change. In order to make the best choices, conscious consumers need a tool to get information on food environment impact, nutritional data and health concerns. The Nutritional App Market is growing rapidly, but far from helping the planet it is unexpectedly incentivizing the consumption of foods with higher carbon footprints.


### How can technology help?

People who want to contribute towards fighting climate change will have access to an easy-to-use platform with nutritional and environmental information, helping them make better choices.

### The idea

We collect data from public databases and user contributions, then we make classifications based on general to more specific foods. This way we give general estimations 
of product environment impact such as CO2 emission, water usage, energy usage and land usage in the making of a product. The goal is that users can easily share and compare
environmental impact vs nutritional value in foods, so they themselves can make better choices for the planet. In order to reach the most people we want to create the best app possible, by making it a social experience, in which users reach their goals together and inspire others to do so.

## Call for code 2022 video

[![](https://i.imgur.com/xszh2dK.jpg)](https://www.youtube.com/watch?v=9ddosvqGiPU)

## Video Demo (English subtitles)

[![](https://i.imgur.com/A2kQve9.jpg)](https://www.youtube.com/watch?v=_8TJStQ3gyc)


## The architecture

![Architecture](https://i.imgur.com/2ATpqyH.jpg)

1. Data is added to our database through user input and open databases such as OpenFoodFacts.
2. Data is cleaned and processed using Python and IBM Watson Studio
3. The mobile application gives users access to the data and all the functionalities.
4. Users can search products using IBM's Speech to Text.
5. Users can search products using the scanner or the search bar.
6. Product information is displayed.
7. Users can share the product data in social media together with inputs/comments of their own.
8. Users can track their fitness and environmental goals.
9. Users can track their diets, log their daily intakes.
10. Users are always aware of both their contribution to the planet and their health.

## Project roadmap

The project currently does the following things.

- Users can search or scan barcodes to get nutritional/environmental information.
- Users can add product data from packages information.
- Product data is regularly processed and classified.

Currently we only have an Android application (not released), we plan on having a web application hosted on IBM Cloud.

See below for our proposed schedule on next steps after Call for Code 2022 submission.

![Roadmap](https://i.imgur.com/Mr1drcR.jpg)

## Getting started

npm install in the root folder
expo start

Test with an Android device or emulator.


## Built with

- [IBM Watson Speech to Text](https://www.ibm.com/cloud/watson-speech-to-text) - The service used to translate speech to text
- [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio) - The software platform to make data analisis
- [React Native](https://reactnative.dev/) - The framework to build everywhere
- [Expo](https://expo.dev/) - Make any app, build it anywhere
- [Python](https://www.python.org/) - The programming language used to make data analisis


## Authors

* Nicolás Millar (Software Developer) - https://www.linkedin.com/in/nicolas-millar-8476161b9/
* Felipe Jiménez (Software Developer) - felipe.jimenez.de.miguel@gmail.com
* Diego Jiménez (Software Developer) - diegojimenez377@gmail.com
* Sebastián Hernández (Medic & Musician) - sebastian.hernandez.teius@gmail.com
* Gabriel Pradenas (Artist & Video Producer) - gabriel.pradenas95@gmail.com


## Acknowledgments

* Cristina Pradenas: Voice in spanish for demo video and logo design
* Francisca: Voice for 3 mins video
* OpenFoodFacts: Food products database made by everyone, for everyone. [Open Food Facts Website](https://world.openfoodfacts.org)