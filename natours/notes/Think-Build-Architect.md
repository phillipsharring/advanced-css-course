# Think Build Architecht

## Think

    * think about the layout of your webpage or web app before writing code

## Build

    * Build your layout in HTML and CSS with a consistent structure for naming classes

## Architect

    * Create a logical architecture for your CSS with files and folders

## Think

    Component-driven design
        * Modular building blocks that make up interfaces
        * Held together by the layout of the page
        * Re-usable across a project, and between different projects
        * Independent, allowing us to use them anywhere on the page

    (Brad Faust atomic design -> molecules -> organisms -> templates -> pages)

## Build

1. Block element modifier BEM
1. Block stand alone component that is meaningful on its own
1. Element part of a block that has no stand alone meaning
1. Modifier a flag/modifier we can put on an element to get a different version of it

## Architect

Create a logical architecture for your CSS with files and folders

### The 7-1 Pattern

7 different folders for partial sass files and 1 main sass file to import all othe rfiles into a compiled css stylesheet

1. base
1. components
1. layout
1. pages
1. themes
1. abstracts
1. vendors
