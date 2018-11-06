### Docker image with latest https://github.com/linkcheck/linkchecker

#### Usage:
``` bash
docker run -ti \
  --rm \
  -v $(pwd)/linkcheckerrc:/root/.linkchecker/linkcheckerrc \
  schliflo/docker-linkchecker \
    --check-extern \
    https://google.com
```

[Config example](https://github.com/schliflo/docker-linkchecker/blob/master/linkcheckerrc)
