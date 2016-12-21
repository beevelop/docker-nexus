[![Travis](https://shields.beevelop.com/travis/beevelop/docker-nexus.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-nexus)
[![Pulls](https://shields.beevelop.com/docker/pulls/beevelop/nexus.svg?style=flat-square)](https://links.beevelop.com/d-nexus)
[![Layers](https://shields.beevelop.com/docker/image/layers/beevelop/nexus/latest.svg?style=flat-square)](https://links.beevelop.com/d-nexus)
[![Size](https://shields.beevelop.com/docker/image/size/beevelop/nexus/latest.svg?style=flat-square)](https://links.beevelop.com/d-nexus)
[![Release](https://shields.beevelop.com/github/release/beevelop/docker-nexus.svg?style=flat-square)](https://github.com/beevelop/docker-nexus/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

> :exclamation: Nexus 3 is still in development and might not be suitable for production **yet**.

# [Sonatype Nexus 3](http://www.sonatype.org/nexus/) for Docker based on Alpine :whale:
----

### Run the image
```bash
docker run -it -p 8081:8081 \
    --name nexus \
    -v `pwd`/data:/opt/nexus/data \
    beevelop/nexus
```

You should then be able to access Nexus via `http://*YOUR_HOST*:8081` and login with `admin:admin123`.
