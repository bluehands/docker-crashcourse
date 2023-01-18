# Docker

## What is Docker?
Docker is a software package that allows one to run and create containers in a simple way.

It uses [containerd](https://containerd.io/) as its base which can create a sandboxed environment. In this environment predefined images containing an application and its dependencies can be executed safely.

![containerd layers](https://containerd.io/img/architecture.png)

## Why use it?

Instead of having to install dependencies to ensure a system is correctly prepared to run a specific application all the dependencies are already in the correct version inside the images.
This makes it also possible to run applications with different versions of the same dependency side-by-side on the same system.

