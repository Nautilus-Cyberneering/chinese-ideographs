## Modify Image ICC Profile GitHub Action

Build docker image:
```
docker build -t change-profile .
```

Run docker image:
```
docker run -e INPUT_SOURCE_IMAGE="input.tif" -e INPUT_DESTINATION_IMAGE="output.tif" -e PROFILE="sRGB" change-profile
```

Run action with `act`:
```
docker image rm act-github-actions-change-image-profile && act -j change-profile
```
You need to remove the previous version of the docker images created by `act`.

## Links

* [`act` docs](https://github.com/nektos/act)