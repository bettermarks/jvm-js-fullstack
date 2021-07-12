[![official JetBrains project](https://jb.gg/badges/official.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub)
[![GitHub license](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg?style=flat)](https://www.apache.org/licenses/LICENSE-2.0)

# Full Stack JVM & JS App Hands-On Lab

This repository is the code corresponding to the hands-on lab [Building a Full Stack Web App with Kotlin Multiplatform](https://play.kotlinlang.org/hands-on/Full%20Stack%20Web%20App%20with%20Kotlin%20Multiplatform/).

We forked it for fullstack hands-on sessions in our recruiting process.

## Start application

Start MongoDB:

    docker-compose -f ./mongo/docker-compose.yml up
    
Start application:

    ./gradlew run
    
Once started the application will be available under:

    http://localhost:9090
    
You should now be able to
- add items to the shopping list via the input field
- remove items by clicking on them