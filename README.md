# OpenID Connect Relying Party Metadata Choices 1.0

This repository contains the OpenID Connect Relying Party Metadata Choices specification.

This specification extends the OpenID Connect Dynamic Client Registration 1.0 specification to enable RPs to express a set of supported values for some RP metadata parameters, rather than just single values. This functionality is particularly useful when Automatic Registration, as defined in OpenID Federation 1.0, is used, since there is no registration response from the OP to tell the RP what choices were made by the OP.

## Builds

The latest released draft of the specification is available at [https://openid.net/specs/openid-connect-rp-metadata-choices-1_0.html](https://openid.net/specs/openid-connect-rp-metadata-choices-1_0.html).

You can view the latest editors' draft at [https://openid.github.io/rp-metadata-choices/main.html](https://openid.github.io/rp-metadata-choices/main.html).

Previews for each branch of this project are automatically built and published at the URL https://openid.github.io/rp-metadata-choices/$branchname.html.
Previews for branches associated with pending Pull Requests are accessible using this pattern.

## Build the HTML ##

```docker run -v `pwd`:/data danielfett/markdown2rfc openid-connect-rp-metadata-choices-1_0.md```

## Contact

For further information and to get involved, please visit the [OpenID Connect Working Group website](https://openid.net/wg/connect/).
