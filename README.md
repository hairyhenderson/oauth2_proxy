# hairyhenderson/oauth2_proxy

This wraps [bitly/oauth2_proxy][] as a very small Docker image. Smaller, in 
fact, than the size of the `oauth2_proxy` binary alone.

I accomplish this with the magic of [multi-stage builds][] and [UPX][]!

See [oauth2_proxy's README][] for details on how to use `oauth2_proxy`.

[bitly/oauth2_proxy]: https://github.com/bitly/oauth2_proxy
[multi-stage builds]: https://docs.docker.com/engine/userguide/eng-image/multistage-build/
[UPX]: https://upx.github.io
[oauth2_proxy's README]: https://github.com/bitly/oauth2_proxy/blob/master/README.md