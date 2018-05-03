# Utterances OAuth
## Required Environment Variables
- `BOT_TOKEN`: A personal access token with `public_repo` scope. You can generate one at https://github.com/settings/tokens
- `CLIENT_ID`, `CLIENT_SECRET`: OAuth application credentials. You can generate them at https://github.com/settings/applications/new
- `STATE_PASSWORD`: A 32 character password. You can generate one with `echo $(tr -dc $([ $# -gt 1 ] && echo $2 || echo "A-Za-z0-9") < /dev/urandom | head -c 32)`
- `ORIGINS`: Comma-separated list of allowed origins
- `APP_ROOT`: The URL for the docker container
