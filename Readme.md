# Home Assistant

This is a stub repo for home assistant docker container.

## Usage

1. Clone/fork this repo.
2. Adjust docker-copose.yaml to your needs.
3. `docker-compose up` to start the container.
4. Go to http://localhost:8123. The default login credentials are:
    ```
    username: admin
    password: raspberrypi
    ```
5. Happy using HA!
6. Configure home assistant as needed, through UI or yaml files. If you have forked the repo, commit & push your changes.

## Configuration

This Home Assistant instance is preconfigured with a default username/password and some default home location - thus it skips the onboarding process. To start from scratch, with onboarding, remove `config/.storage` directory.

To change basic home settings, edit `homeassistant` section in `config/configuration.yaml`.