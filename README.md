# example-webapp
For storing the sample code from Linked learning

Build the image on docker desktop with:
- docker build --tag webserver:skv1 -f Dockerfile .

Run the webserver on docker desktop with:
- docker run -dit --name my-running-app -p 8080:80 webserver:skv1
