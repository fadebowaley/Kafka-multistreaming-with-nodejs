# Multi-Stream Kafka App

This is a Nodejs-based Kafka app that allows you to publish and consume data from multiple Kafka servers simultaneously.

## Installation
- Clone this repository to your local machine.
Install the required packages using the following command:

`npm init`
Set up the Kafka hosts and topics in the.

## Usage
Open three separate terminal windows.

- In the first window, run the following command to create Kafka topics for each server:
`npm start producer.js`

- In the second window, run the following command to publish data to each server:
`node ./consumer.js`


## Configuration
The .env file contains the configuration for each Kafka server, including the host and topic name. Modify this file as needed to add or remove servers.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License

MIT