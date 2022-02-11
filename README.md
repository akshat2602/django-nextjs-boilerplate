
# Django-Next-Template!
This is a basic starter template for a fullstack web project with Django as the server, PostgreSQL as the database and Next.js as the frontend. 

## About the template 
-   PostgreSQL used as the primary database.
-   Superuser is already initialized with the credentials: Username- `admin`, Email- `admin@admin.com`, Password- `admin`
-    Integration with Django Rest Framework
-   Integrated Djoser for user register/login/logout workflows.
-   Used JWT for Authentication.
-   API Documentation is configured using swagger.
-   Containerized using Docker and managed using docker-compose.
-   A typescripted Next.js client has been preinstalled and integrated with docker-compose.

## Getting Started
To get a local copy of this template up and running on your machine, follow these simple steps.
### Prerequisites
- Docker
`curl -fsSL https://get.docker.com -o get-docker.sh`
`sudo sh get-docker.sh`

### Installation
- Clone the repo `git clone https://github.com/akshat2602/django-nextjs-template.git`
- Change the current directory to the template `cd django-nextjs-template`
- Build the docker containers`docker-compose -f docker-compose.dev.yml build` for the dev containers and `docker-compose -f docker-compose.prod.yml build` for the prod containers
- Run the docker containers`docker-compose -f docker-compose.dev.yml up` for the dev containers and `docker-compose -f docker-compose.prod.yml up` for the prod containers

## API Documentation
API documentation is done using swagger. Visit `/swagger` for API documentation.

## Roadmap
See the [open issues](https://github.com/akshat2602/django-nextjs-template/issues) for a list of proposed features (and known issues).

## Contributing
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Akshat Sharma - [akshatsharma2602@gmail.com](mailto:akshatsharma2602@gmail.com)
Project Link: [https://github.com/akshat2602/django-nextjs-template](https://github.com/akshat2602/django-nextjs-template)

