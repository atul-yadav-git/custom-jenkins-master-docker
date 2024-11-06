To automate the installation of the Docker CLI in your Jenkins container, you can create a custom Docker image based on the official Jenkins image. This way, every time you run your Jenkins container, it will have Docker CLI installed and ready to communicate with the host Docker daemon.

so im using official jenkins image as base image and on top of it installing docker cli and making it as my custom image

so that i can use jenkins as docker container to run docker task like docker in docker kind of situation
