# Maintaining

## Releasing a New Version

### Updating and Deploying Dashboard

1. Update `version` in [package.json](https://github.com/yorkie-team/dashboard/blob/main/package.json#L36).
2. Update `REACT_APP_JS_SDK_VERSION` in [.env](https://github.com/yorkie-team/dashboard/blob/main/.env#L2).
3. Update version of Yorkie image in [docker/docker-compose.yml](https://github.com/yorkie-team/dashboard/blob/main/docker/docker-compose.yml#L26).
4. Create Pull Request and merge it into main.
