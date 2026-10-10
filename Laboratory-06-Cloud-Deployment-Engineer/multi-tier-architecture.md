# Two-Tier Architecture

A Two-Tier Architecture is a system that has two main parts: the application and the database. These two parts work together so users can use the application and save their data.

## The Web/Application Tier

The Web/Application Tier is responsible for showing the user interface, handling requests, and running the application. In our laboratory, the Nextcloud container serves as the application where users can access and manage their files.

## The Database Tier

The Database Tier stores important information such as user accounts and file metadata. In our laboratory, the MariaDB container is used to store and manage the data needed by Nextcloud.

## Why Separate Them?

Separating the application and database makes the system more organized and easier to manage. It also allows each part to be updated or maintained separately. This setup can make the application easier to scale and help manage its resources efficiently.
