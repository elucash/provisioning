provisioning
============

Uncustomized sample installation could be done with this line

```sh
curl -L https://raw.github.com/immutables/provisioning/master/install | bash
```

What you need to do is to create directory, change to that directory and launch above command.
All new scripts and repositories will be downloaded to current directory.
Customize by exporting special variables:

```sh
# configuration and deployment git repository base
export IM_ORIGIN=https://github.com/immutables
# production branch in configuration repository
export IM_PRESET=production
```

It is highly recommended to create your own single copy-paste command installation with customization.
