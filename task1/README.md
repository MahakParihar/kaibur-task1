# Task 1

**NOTE:** [README First](/README.md)

## Building steps

1. Open the folder `/task1` in your favourite IDE ( VS Code :heart:)
Wait for few minutes while the IDE loads and completes necessary pre-build tasks.

2. Run `mvn clean install`
This will build and install the artifacts in to the local repository.
Required jar file will be created inside `/target` folder.

3. Run the application by clicking `Run` option or pressing `F9`
SpringBoot application server will load and start on port `8080` of the `localhost`.

## Rest  API Endpoints and Resources
Rest API Endpoint is mapped to `http://127.0.0.1:8080/servers/`

- GET servers	`http://127.0.0.1:8080/servers/getServer`
Returns list of "server" objs.

- PUT a server	`http://127.0.0.1:8080/servers/createServer`
Accept "server" obj in json format.

- GET server	by ID	`http://127.0.0.1:8080/servers/getServer?id=<ID>`
Returns a  "server" obj with matching ID.

- GET servers	by Name	`http://127.0.0.1:8080/servers/getServer?name=<Nmae>`
Returns a list of "server" objs withn matching Name.

- DELETE server	`http://127.0.0.1:8080/servers/deleteServer?id=<ID>`
Deletes a  "server" obj with matching ID.