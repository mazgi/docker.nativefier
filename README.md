# docker.nativefier
Dockerfile for Nativefier

## Examples

```shellsession
$ docker run -v $PWD:/pwd -it mazgi/nativefier nativefier --platform osx --counter --bounce --name "GCP Console(YOUR_GOOGLE_ACCOUNT_NAME)" console.cloud.google.com
```

```shellsession
$ docker run -v $PWD:/pwd -it mazgi/nativefier nativefier --platform osx --counter --bounce --name "AWS Console(YOUR_AWS_ACCOUNT_NAME)" console.aws.amazon.com
```
