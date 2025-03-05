# ROS_1_Docker_Template
Template Repo for ROS2 Docker based deployment for the usage at @HKA-IRAS based on the concepts of [@AndreasZachariae](https://github.com/AndreasZachariae)

Extend the provided `Dockerfile` for your own projekt. Local files for development can be used within the docker by moving them into the `src` folder.\
Additional packages can be installed within the `Global Dependencies` step within the `Dockerfile`, using apt and pip.\
If you need to install dependencies from source add them to the dependency workspace within the `Dockerfile`.\

Ensure that you give your docker a meaningful name and adjust the tag to your used setup. These changes must be done within the `build_docker.sh` and `start_docker.sh` file.

# MY_PROJECT
This is your space to describe your project. What is it for, how can it be installed and used? Keep it simple, use sample commands where possible. For the full markdown syntax take a look at: [Github Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
