# renovate-bot-test-repo

sample repo to test the working of renovate bot

```console

docker run --rm \
          -v "$(pwd):/usr/src/app" \
          -v ~/.aws:/root/.aws:ro \
          -e RENOVATE_TOKEN=$RENOVATE_TOKEN \
          -e AWS_PROFILE=$AWS_PROFILE \
          -e LOG_LEVEL=debug \
          renovate/renovate Aniket-More-19/renovate-bot-test-repo

```
