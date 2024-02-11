# The project "Positivus"

### Layout of the [layout](https://www.figma.com/file/E01bo1VFBKyQgqUbel7NXA/Positivus-Landing-Page-Design-(Community)?type=design&t=orhpiX1MFM9I0acC-6) "Positivus"

#### Link to the project:
https://slavawebdeveloper.github.io/Positivus/

## About the project
The HTML code is completely written according to the BEM methodology. The project does not include js. Only html and scss (=> css).  Including dialog and using only css capabilities (scroll-snap-type) implemented the slider feature (instead of npm swiperjs).The issues related to the accessibility of the interface are taken into account.
The color palette changes automatically depending on the user's preferences.

## Installation

git clone https://github.com/SlavaWebDeveloper/Positivus.git

npm install 

### For local development, use:
npm run dev 

### To build a project, use:
npm run build

## Stack
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![css3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![Gulp](https://img.shields.io/badge/GULP-%23CF4647.svg?style=for-the-badge&logo=gulp&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## File Tree:
Positivus    
├── src  
│   ├── fonts  
│   │   └── ...  
│   ├── images  
│   │   ├── favicon  
│   │   │   └── ...  
│   │   ├── icons  
│   │   │   └── ...  
│   │   ├── partners  
│   │   │   └── ...  
│   │   ├── service  
│   │   │   └── ...  
│   │   ├── team  
│   │   │   └── ...  
│   │   └── ...  
│   ├── js  
│   ├── styles  
│   │   ├── blocks  
│   │   │   └── _banner.scss  
│   │   │   └── _burger-button.scss  
│   │   │   └── _button.scss  
│   │   │   └── _contact-us.scss  
│   │   │   └── _cross-button.scss  
│   │   │   └── _field.scss  
│   │   │   └── _footer.scss  
│   │   │   └── _grid.scss  
│   │   │   └── _header.scss  
│   │   │   └── _hero.scss  
│   │   │   └── _mobile-overlay.scss  
│   │   │   └── _pagination.scss  
│   │   │   └── _process.scss  
│   │   │   └── _puddle.scss  
│   │   │   └── _radio.scss  
│   │   │   └── _radios.scss  
│   │   │   └── _review-card.scss  
│   │   │   └── _reviews.scss  
│   │   │   └── _section.scss  
│   │   │   └── _service-card.scss  
│   │   │   └── _services.scss  
│   │   │   └── _soc1als.scss  
│   │   │   └── _studie.scss  
│   │   │   └── _subscribe-form.scss  
│   │   │   └── _team-card.scss  
│   │   │   └── _team.scss  
│   │   └── _fonts.scss  
│   │   └── _globals.scss  
│   │   └── _media.scss  
│   │   └── _mixins.scss  
│   │   └── _normalize.scss  
│   │   └── _themes.scss  
│   │   └── _utils.scss  
│   │   └── _variables.scss  
│   │   └── style.scss  
│   └── index.html  
└── .gitignore  
└── gulpfile.js  
└── package-lock.json  
└── package.json  
└── README.md  