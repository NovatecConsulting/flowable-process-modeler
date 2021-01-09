## Flowable Process Modeler App

This project contains a spring boot application to launch the web based flowable process modeler app. 
Alternatively you can download the flowable war file and deploy it yourself.

**There is currently no standalone Desktop version of the modeler available**

## How to run it

- Start the application like a regular spring boot application
    - Run `./gradlew bootRun` or via IntelliJ in the main class `FlowableModeler.java`
    - Open the ui app under `http://localhost:8080/idm/#/login`
    - Enter the credentials `admin:test`
- Open the app "Modeler App" in the UI
- Start creating your process models