# Quick start
## Step 1. Set up .env
Copy .env_example and save it as .env, edit as you like

## Step 2. Pull down the images from the Docker Hub
 % docker-compose pull
 Pulling strapiexample ... done  
 Pulling mongoexample  ... done  

## Step 3. Run the stack
 % docker-compose up -d
 Creating network "strapi-docker-composer-example_strapi-app-network" with driver "bridge"  
 Creating volume "strapi-docker-composer-example_strapidata" with default driver  
 Creating strapiexample ... done  
 Creating mongoexample  ... done  

## Step 4. Open Backend
 http://localhost:1337/admin


# References 
https://strapi.io/blog/how-to-run-a-strapi-dev-stack-with-docker-compose