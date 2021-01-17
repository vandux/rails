## Unreleased

*   Change `content_security_policy_report_only` and associated middleware to
    support blocks, similar to `content_security_policy`.

    This allows for requests to have both Content-Security-Policy and
    Content-Security-Policy-Report-Only headers.

    The changes are backwards compatible.

    Fixes #40452

    *Shaun Russell*

*   Change the request method to a `GET` when passing failed requests down to `config.exceptions_app`.

    *Alex Robbin*

*   Add `redirect_back_or_to(fallback_location, **)` as a more aesthetically pleasing version of `redirect_back fallback_location:, **`.
    The old method name is retained without explicit deprecation.

    *DHH*


Please check [6-1-stable](https://github.com/rails/rails/blob/6-1-stable/actionpack/CHANGELOG.md) for previous changes.
