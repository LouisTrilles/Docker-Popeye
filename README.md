
# 🐬 Popeye Docker  | Louis Trilles
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

The purpose of the **Docker** project is to familiarize ourselves with containers.

**3** Dockerfiles and **1** Dockercompose had to be made in 4 days to make the project work.

## 📚 Documentation

You will find with the repository, a documentation written by me which resumes the functioning of Docker, and how I had to adapt the files provided by Epitech so that they are functional with the docker-compose.

Also, the subject is available if you wish to consult it.

## ⚙️ Docker commands

To deploy this project run:

```javascript
  docker-compose up --build
```
Check if the container is running:

```javascript
  docker ps -a
```

Shut down all containers:

```javascript
  docker-compose down -v
```

Delete all containers (including volumes, images):


```javascript
  docker system prune -a --volumes
```

## Result of my.epitech.eu

| Images        | Build and test           | Percentage  |
| ------------- |:-------------:| -----:|
| Poll     | ✔️ | 100% |
| Result     | ✔️      |   100% |
| Worker | ✔️ |     100% |

| Docker Compose        | Build and test           | Percentage  |
| ------------- |:-------------:| -----:|
| Service poll     | ✔️ | 100% |
| Service redis      | ✔️      |   100% |
| Service worker | ✔️      |    100% |
| Service db | ✔️      |    100% |
| Service result | ✔️      |    100%|
| Volumes | ✔️      |    100%|
| Networks |✔️     |    100%|



## 📬 Contact

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/louis-trilles//)
