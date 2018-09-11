# delta-consul

This docker container is basically [consul](https://hub.docker.com/r/_/consul/) with mysql-client, python, perl and bash for the ability of running more advanced service checks.

#### upgrading

To get the latest consul release, simply create a new tag, and docker hub will build a new release matching tag version with *consul:latest*
Example:

```bash
$ git tag v1.2
$ git push origin --tags
Total 0 (delta 0), reused 0 (delta 0)
To github.com:deltaprojects/delta-consul.git
 * [new tag]         v1.2 -> v1.2
```

Afterwards you can see build status at https://hub.docker.com/r/deltaprojects/delta-consul/builds/.
