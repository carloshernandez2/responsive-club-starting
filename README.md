# Project Name

> POSTRES ABUELA BEATRY.

## Table of contents

- [Project Name](#project-name)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Features](#features)
  - [Status](#status)
  - [Inspiration](#inspiration)
  - [Contact](#contact)

## General info

The purpose of the proyect is to use flexbox to design and build the layout for a company’s homepage.

## Screenshots

Background image screenshot:

![Example screenshot](./Images/postre-de-limón-background.jpg)

## Technologies

- CSS flexbox
- CSS grid
- HTML

## Setup

[Home page in GitHub Pages](https://carloshernandez2.github.io/flexbox-business-site-starting/)

## Code Examples

Example of usage:

```css
main {
    position: relative;
    top: 70px;
    width: 90%;
    margin: 0 auto;
    display: grid;
    grid-template: 3fr 1fr repeat(4, 3fr) 1fr 3fr 3fr / repeat(2, auto);
    gap: 1vmin;
    grid-template-areas: "mission mission"
                         "titulo1 titulo1"
                         "producto1 descri1"
                         "descri2 producto2"
                         "producto3 descri3"
                         "descri4 producto4"
                         "titulo2 titulo2"
                         "emp1 descri5"
                         "descri6 emp2";
}
```

## Features

List of features:

- Responsive homepage
- Grid layout
- Flexbox layout

## Status

Project is: Finished.

## Inspiration

I was motivated by the idea of a fictional dessert shop for my grandma.

## Contact

Created by [@CarlosHernández](https://linkedin.com/in/carlos-manuel-hernández-consuegra-42975a189) - feel free to contact me!
