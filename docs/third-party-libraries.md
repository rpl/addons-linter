# About 3rd Party Libraries in Add-ons

We maintain a list of banned and unadvised third-party JavaScript libraries; these libraries are not allowed/recommended in add-ons (because of security vulnerabilities).

## Banned libraries

### AngularJS `1.x`

AngularJS `1.x` versions below `1.5.9` are not allowed due to a [CSP vulnerability](http://www.slideshare.net/x00mario/an-abusive-relationship-with-angularjs).

We allow `1.5.9` and above; all previous versions are banned.

### jQuery `1.x`

jQuery versions older than 2.0 are not supported by the jQuery team for development inside extensions. Please use a recent version.
