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



docker run --rm \
  -v "$(pwd):/usr/src/app" \
  -e RENOVATE_TOKEN=$RENOVATE_TOKEN \
  -e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID \
  -e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY \
  -e AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION \
  renovate/renovate Aniket-More-19/renovate-bot-test-repo


```
