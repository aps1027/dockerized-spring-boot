### Production Mode
1. Run docker compose
    ```
    $ docker-compose -f docker-compose-prod.yml up
    ```

### Development Mode
1. Run docker compose
    ```
    $ docker-compose up
    ```

### Live Reload For Development Mode
1. Install `VS Code Remote Development`
    ```
    https://code.visualstudio.com/docs/remote/remote-overview
    ```
1. Run docker compose from Terminal
    ```
    $ docker-compose up
    ```

1. Open Folder in constainer from Remote Explorer

1. Install `Java Extension Pack` and `Spring Boot Tools` inside constainer
    ```
    https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack

    https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-spring-boot
    ```

1. Make sure to import Java (Maybe: notification will appear to import java)

1. Make some changes in your code and check in browser.