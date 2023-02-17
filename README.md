[![workflow](https://github.com/rumeysakdogan/my-gha-project/actions/workflows/ci.yml/badge.svg)](https://github.com/rumeysakdogan/my-gha-project/actions/workflows/ci.yml)

##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
