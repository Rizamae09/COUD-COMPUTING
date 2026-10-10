# Two-Tier Architecture

## The Web/Application Tier

The Web/Application Tier is the part that users interact with. It handles requests from users and provides the web interface. In this activity, Nextcloud is used as the web application that users can open and access through a browser.

## The Database Tier

The Database Tier is where the application's important data is stored. For this activity, MariaDB is used as the database for Nextcloud. It stores information needed by the application, including user-related data.

## Why Separate Them?

Having the web application and database in separate containers makes the system easier to manage. Each container has its own job, but they can still communicate with each other when needed. This also makes it easier to maintain or make changes to one part without affecting the other.
