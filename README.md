# gitlab-runner

Forked and improved from @abelfodil/gitlab-runner.

Auto-registering gitlab-runner. You just need to supply the registration token and runners are automatically registered, started and ready to use in Gitlab.

## Configure

- Copy `.env.example` to `.env`.

- Change `GITLAB_INSTANCE_URL` according to your needs

- Add registration token to `REGISTRATION_TOKEN`.

- Set `DESCRIPTION` to whatever you want (usually the hostname).

- Add allowed-to-run tags seperated by comma to `TAG_LIST`.

## Run

Register and start the Gitlab Runner by running `docker-compose up -d`.

## Stop

Stop the runner by running `docker-compose down`.
