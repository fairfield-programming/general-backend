# ![General Backend Server](https://raw.githubusercontent.com/fairfield-programming/general-backend/d713030a373176dc41757806223cadf6bf61a89c/.github/media/cover.svg)

This is the general backend server code for the Fairfield Programming Association. All of the code in this project is licensed under the [ISC License](https://opensource.org/licenses/ISC)- all contributions are welcome.

## Code and API Reference

### API Objects

```mermaid

classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
      +String beakColor
      +swim()
      +quack()
    }
    class Fish{
      -int sizeInFeet
      -canEat()
    }
    class Zebra{
      +bool is_wild
      +run()
    }

```