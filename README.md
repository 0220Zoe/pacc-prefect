# pacc-prefect

An orchestration tool to build, observe, and react to data pipeline

## Getting Started

1. after pip Prefect, create flow and tasks in Python script, then run it in local Prefect and then create deployment
2. Then you push the definition to the server (server is the local host) / user prefect Cloud for the same purpose;


## Usage

How to use the project, including code examples://
prefect deployment build weatherflow.py:fetch_weather -n new-deployment
prefect deployment apply fetch_weather-deployment.yaml
prefect deployment build weatherflow.py:fetch_weather -n new-deployment -sb github/prefect-repo

## Contributing

Prefect supports scheduling, alerting, and data extraction, all from a centralized location.

## License

This project is licensed under the [MIT License](LICENSE).
