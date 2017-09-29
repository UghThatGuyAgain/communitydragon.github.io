# Introduction
## Background
The company "Riot Games" owns and develops a game called "League of Legends". Riot Games provides a public API and CDN for this game. The static data provided by the API and the CDN are named as "Data Dragon". the problem arises when Data Dragon does not fix the issues within the static data and lacks assets that third party developers would like to use. This community under the name "Community Dragon" has been founded with the goal to tackle the issues that Data Dragon provides. 

## Goals
The goals for this project are simple:
* Create an API to give developers an alternative to data dragon.
  * This API will manage the inconsistent and not updated data provided by Data Dragon.
  * This API  will provide extended and aditional data that Data dragon currently does not provide. 

## Contributors
* [Sandi Karajic](https://github.com/skarajic) (Project Leader, Full Stack Developer)
* [Matthew Oslan](https://github.com/derpthemeus) (Back-End Developer)
* [Querijn](https://github.com/querijn) (Back-End Developer)
* [costpermille](https://github.com/querijn) (Full Stack Developer)
* [stelar7](https://github.com/stelar7) (Full Stack Developer)
* [dvgaba](https://github.com/dvgaba) (Full Stack Developer)
* SkinSpotLights (Contributor, ?)
* Tuxedo (Contributor, ?)

<br/>

---

# Terminology

<table>
    <tr>
        <th>Term</th>
        <th>Definition</th>
    </tr>
    <tr>
        <td>Terms</td>
        <td>To be added</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>-</td>
        <td>-</td>
    </tr>
</table>

<br/>

---

# Back-End
## Goals
The goals for the back-end are as following:
* Relink existing assets from ddragon and reroute them as part of cdragon.
* Set up a way to pull data from ddragon, improve it and set up an endpoint for it (currently there is a library being developed by [Querijn](https://github.com/querijn) for differenciating data called [DiffDragon](https://github.com/Querijn/DiffDragon)).
* Set up accounts to be able to manually add and change data.
* Set up a way to add images and asign them an endpoint.

## Setup
The REST API will be hosted on a NodeJS server with a (TBD) database with the domain being https://api.cdragon.com/. The API will be developed in TypeScript & ES6/ES7.

## Tools
For unit & integration testing the frameworks [Mocha](https://mochajs.org/) and [Chai](http://chaijs.com/) will be used. Builds will be tested by [Travis-CI](https://travis-ci.org/).

<br/>

---

# Front-End