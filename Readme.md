# Ubuntu SSH Dockerfile

This Dockerfile creates an Ubuntu-based Docker image with SSH access, allowing you to set up multiple instances of an Ubuntu server. The root user has a default password, and you can customize it during the build process.

## Features

- **SSH Access:** Provides SSH access for easy management and configuration.
- **Customizable Root Password:** You can set a custom root password during the build process.

## Usage

1. **Build the Docker Image:**
   ```bash
   docker build --build-arg ROOT_PASSWORD=my_secure_password -t ubuntu-ssh .
