# Go K8s Project

### Overview

This is a learning project to practice containerizing apps and managing them through
kubernetes. The goal is to apply this to other projects and allow this repo to simply
be a playground for experimentation. The tutorial I followed to get the basics down
can be found here:
</br>
https://www.coding-bootcamps.com/blog/build-containerized-applications-with-golang-on-kubernetes.html
</br>

### Components

#### Go App
The app here is incredible simple: a "hello world" app. Nothing fancy but a chance to
setup a quick endpoint with health check and good Go hygiene.
</br>
#### Docker
The Dockerfile here is multistage so I can run tests, build, etc, but only containerize
the pieces I need for the app.
</br>
#### Kubernetes
The k8s manifest included here has a Deployment config and a Service config. This is
where most of my experimentation will be for this project as there are countless
other settings to try or other configs to add.
