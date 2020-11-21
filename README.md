# Build images

```sh
docker build --tag ghcr.io/8-bit-fox/tw-$OS:$TAG -f Dockerfile-$OS .
docker push ghcr.io/8-bit-fox/tw-$OS:$TAG
```
Open Github, go to packages, make package public. Use action.

