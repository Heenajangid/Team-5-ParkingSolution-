# Team-5-ParkingSolution-
<img width="1436" alt="parking solution" src="https://github.com/user-attachments/assets/8f14a14a-b738-4876-abaa-10a5c85c039a">


## Docker file setup 
### Required steps:
``` 1. base image alpine, heenaimage 
    2. dependent libraries -> install 
    3. main.py -> copy local to inside docker
    4. run main.py ```

## Jenkins pipeline file creation (CI/CD)
``` Step 1. when first job will run then jenkins take the code and keep it inside at jenkins workspace 
    Step 2. create a docker image(version wise using build environment value) run using build command ->
    Step 3. image pull and push ( jo bhi environment m ayegi)
    Step 4. run the latest image (every time) ```

