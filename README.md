## About Tasks Super Manager

This is a test application for ZagaLabs. You can find here documentation on how to download and run this application.

Any question, please reach out to jsleald@gmail.com

## Pre requisites
This document has beed developed considering you have a Windows machine. However, most of the information should work for other platforms.
* Git
* Bash terminal
* Browser (Chrome)
* Docker

## How tu use it

* Clone this project in you machine.
* Create the Docker image:
```docker build -t tasks_manager_image .```
* Execute the image, create the container that serves the app:
```docker run -p 8181:8181 tasks_manager_image```
* Run the application in your browser:
```http://localhost:8181```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
