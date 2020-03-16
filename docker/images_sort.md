# Sort Docker image by size

```docker images --format '{{.Size}}\t{{.Repository}}\t{{.Tag}}\t{{.ID}}' | sed 's/ //' | sort -h -r | column -t```

REF: [docker-image-size.sh](https://gist.github.com/andyrbell/f30ae74c0eff82ae52238f4a7df9a313)
