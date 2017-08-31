# Kirby Base for Docker

This is a base project for working with [Kirby CMS](https://getkirby.com) and [Docker](https://www.docker.com).

# Usage

- Download and install Docker
- Download or clone the repo.
- Choose either the starterkit or the plainkit.
- Copy your chosen project and rename it
- In the project run:

``docker-compose up -d``

To see the site, visit:

``http://localhost``

To setup and use the Kirby Panel visit:

``http://localhost/panel``

Make changes to your project in *content*, *assets* and *site*.

To stop the container:

``docker-compose down``

Your changes will persit in the *content*, *assets* and *site* directories.
