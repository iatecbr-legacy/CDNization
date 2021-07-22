# CDNization

Sometimes it is necessary to consume third-party static files, after all there is no reason to reinvent the wheel, [but these are not always available on a CDN or we are able to do this safely](https://hacks.mozilla.org/2015/09/subresource-integrity-in-firefox-43/).

For the sake of security, [at least something basic like an integrity check should be done](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) and for this reason this repository was created.

To avoid unnecessary costs when using [this excellent free CDN](https://www.jsdelivr.com/?docs=gh), we gained in addition to the CDN structure the ability to use [SRI](https://www.srihash.org/).

[To use it's that simple](https://www.jsdelivr.com/github).
