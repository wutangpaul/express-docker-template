
# How this works

## Build the image

    docker build -t wutangpaul/da-bread-zone-website .

## Check the image has been built successfully

    docker images

## Build a new container instance

    docker run --name da-bread-zone-website -p 80:8080 -d wutangpaul/da-bread-zone-website

## Make sure container is running

    docker ps

## Visit website

You should now be able to see your application running on http://localhost:80/