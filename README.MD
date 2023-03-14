This example is based on https://github.com/viglucci/app-jcef-example 

To start it correctly we should:
- pass Java args
    ```
    -Djava.library.path=${HOME}/projects/jcef/distrib/bin/lib/linux64
    --illegal-access=permit 
    --add-opens=java.desktop/sun.awt=ALL-UNNAMED
  ```
- set env. variable
    ```LD_LIBRARY_PATH=/usr/lib/jvm/java-17-openjdk-amd64/lib```