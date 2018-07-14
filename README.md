# OssDoc

OssDoc is a fork of [UniDoc](https://github.com/unidoc/unidoc), which is a powerful PDF library for Go (golang).

Difference from UniDoc:

  - UniDoc has dual license: AGPL and a commercial license.  OssDoc uses only AGPL license.

  - UniDoc requires the users to order a license from [https://unidoc.io](https://unidoc.io).
    OssDoc doesn't have such requirements and all the license checking code has been removed.

Users of this library must obey the terms of AGPL (see [LICENSE.md](./LICENSE.md))

## Installation

Add following lines into your Gopkg.toml:

```
[[constraint]]
  name = "github.com/unidoc/unidoc"
  branch = "master"
  source = "github.com/gtrafimenkov/ossdoc"
```

## Copyright

OssDoc is a fork of UniDoc.

UniDoc has the following copyright:

```
UniDoc - PDF library for golang
Copyright (C) 2016-2017 FoxyUtils ehf.

This program provided by FoxyUtils ehf ("Company") is free software ("covered
work"). You can redistribute it and/or modify it under the terms of the GNU
Affero General Public License, Version 3 ("License") which is currently located
here ?http://www.gnu.org/licenses/agpl.html (and listed in full below), with
the addition of the following permission added to Section 15 as permitted in
Section 7(a): FOR ANY PART OF THE COVERED WORK IN WHICH THE COPYRIGHT IS
OWNED BY THE COMPANY, THE COMPANY DISCLAIMS THE WARRANTY OF NON INFRINGEMENT
OF THIRD PARTY RIGHTS. YOU USE THIS WORK AT YOUR OWN RISK.

This covered work is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY, without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the License for further details.

The interactive user interfaces in modified source and object code versions of
this covered work must display Appropriate Legal Notices, as required under
Section 5 of the License.

You can be released from the requirements of the license by purchasing a
commercial license. Buying such a license is mandatory as soon as you develop
activities involving UniDoc without disclosing the source code of your own
applications under the AGPL license. These activities include offering services
as an application service provider or providing an over-network based
application programming interface (API), creating or manipulating documents for
users in a web/server/cloud application, incorporating UniDoc into a closed
source product.

For more information, please contact the Company by emailing sales@unidoc.io.
```
