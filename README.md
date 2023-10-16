## API Data Fetcher

### Description

This Python project fetches data from an API and saves it to a CSV file.

### Usage

**Without Docker:**

To run the project without Docker, run the following command:

```shell
python main.py
```

**With Docker:**

To run the project in a Docker container, run the following command:

```shell
docker-compose up -d
```

This will start a Docker container with the project installed. You can then access the project from the container by running the following command:

```shell
docker exec -it api-data-fetcher python main.py
```

**Requirements:**

This project requires the following Python packages:

```
- requests
- pandas
```

To install the required packages, run the following command:

```shell
pip install requests pandas
```

**Folder structure:**

The project folder structure is as follows:

```
my_project/
├── api_data.csv
├── docker-compose.yml
├── Dockerfile
├── requirements.txt
├── setup.py
└── src/
    ├── __init__.py
    ├── main.py
    └── tests/
        ├── test_main.py
```

**License:**

This project is licensed under the `MIT License`.

**docker build -t api-data-fetcher .:**

```
* You can also use the Dockerfile and docker-compose.yml files to deploy the project to a production environment. For example, you could use a cloud-based Docker registry to store the Docker image, and you could use a Kubernetes cluster to run the project in production.
```
