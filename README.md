# Yolo Project

- Yolo Project is a simple web application that consists of a Node.js-based API (backend) and a React-based frontend. It uses Docker and Docker Compose to run the application in containers, making it easy to set up and deploy.

## Prerequisites

- Before you get started, make sure you have the following software installed on your system:

- Vagrant (https://www.vagrantup.com/)
- VirtualBox (https://www.virtualbox.org/)

## Getting Started

- Clone the Yolo Project repository to your local machine:

    ```bash
    git clone https://github.com/MungaiVic/yolo.git

    ```

- Change into the project directory:

    ```bash
    cd yolo
    ```

- Start the Vagrant virtual machine:

    ```bash
    vagrant up --provision
    ```

- This will provision all that's needed to run the application using docker in the vm.
