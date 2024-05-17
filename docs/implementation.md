# Implementation 
## Introduction
The application is both a web and app development project used to ping locations on a map based on a users geolocation. Using various data sources, we are able to provide accurate and reliable data for our users no matter which greenspace they pick!
// expand more later 

### Our structure:
Greenscapes runs primarily from 2 apis, the first of which is OpenStreetMaps API to provide us with accurate and real time imaging of the greenscape and the users geolocation. The second API we use is Bristol open data (https://opendata.bristol.gov.uk/datasets/a5b3c152b9894127a64bd3b03318ad0a_3/explore). Currently, we only operate with the Bristol Open Data as a primary information source for our users with plans to expand further down the line to support more and more places nationally. To give our users the best experience, we ping their current geolocation, with their permission, inline with our system which displays all over the Bristol area the best and most notable greenspaces near them. 
### Project internal structure
The internal structure of the Greenscapes project can be found here:
```
└── 📁Greenscapes.github.io
    └── 📁app
        └── FindNearestGreenspaces.html
        └── GreenspacesMapSearchUI.html
        └── LoginPage.html
    └── 📁docs
        └── 📁Images
            └── GreenspacesHomeUI.jpg
            └── GreenspacesSearchPageUI.jpg
            └── GreenspacesSearchUI.jpg
        └── deployment.md
        └── design.md
        └── implementation.md
        └── planning.md
        └── requirements.md
        └── testing.md
    └── readme.md
```
