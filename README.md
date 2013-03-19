Simple [riemann-dash](https://github.com/aphyr/riemann-dash/) wrapper
which gets deployed like any other service.

The most important difference over the standard **riemann-dash** is that
the web server can handle static assets directly. Thin should only
handle Ruby code, not static files.
