# playground-packer
Trying out packer to build docker containers. Turns out at the time of writing
there's no way to set docker entry point variables which makes packer useless
for what we're trying to do. Derp.

## Usage
```sh
$ ./build
```

## See Also
- https://www.packer.io/docs/builders/docker.html
- https://www.packer.io/docs/post-processors/docker-tag.html
- https://github.com/GoogleCloudPlatform/kube-jenkins-imager
- https://www.packer.io/docs/templates/user-variables.html
- https://github.com/GoogleCloudPlatform/kube-jenkins-imager
- https://www.packer.io/docs/templates/provisioners.html

## License
[MIT](https://tldrlegal.com/license/mit-license)
