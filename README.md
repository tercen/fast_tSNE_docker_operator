# Fast t-SNE Docker Operator

##### Build the image

```bash
VERSION=0.0.1
docker build -t tercen/fast_tSNE_docker_operator:$VERSION .
docker push tercen/fast_tSNE_docker_operator:$VERSION
git add -A && git commit -m "$VERSION" && git tag  $VERSION  && git push && git push --tags
```
