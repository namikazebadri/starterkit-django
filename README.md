# Django Docker Image

Build docker image for Django application.

## Build Image
To build image run this command (__change the tag name with your preferred tag name__).

`$ docker build . -t myorganization/myimage:1.0.0`

## Running Container from Image

To create a container from the image, run this command (__change the tag name with your preferred tag name__).

`$ docker run -d -p 8000:8000 --name django-app myorganization/myimage:1.0.0`

Then you can access the app from the browser with this url: `http:127.0.0.1:8000`