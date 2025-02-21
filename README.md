# Clasp sandbox

## Usage

1. login
   ```shell
   docker compose run --rm --service-ports node clasp login --redirect-port 3000
   ```

## Add a new script

1. Run
   ```shell
   docker compose up -d
   ```
2. Exec
    ```shell
    docker compose exec node bash
    ```
3. Copy
    ```shell
    cp -r /app/templates/app-template /app/apps/<app-name>
    ```
4. Change directory
    ```shell
    cd /app/apps/<app-name>
    ```
5. install
    ```shell
    npm i 
    ```
6. Login
    ```shell
    clasp login --redirect-port 3000
    ```
7. Create
    ```shell
    clasp create
    ```
