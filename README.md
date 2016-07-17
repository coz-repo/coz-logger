coz-logger
==========

<!---
This file is generated by ape-tmpl. Do not update manually.
--->

<!-- Badge Start -->
<a name="badges"></a>

[![Build Status][bd_travis_shield_url]][bd_travis_url]
[![Code Climate][bd_codeclimate_shield_url]][bd_codeclimate_url]
[![Code Coverage][bd_codeclimate_coverage_shield_url]][bd_codeclimate_url]
[![npm Version][bd_npm_shield_url]][bd_npm_url]
[![JS Standard][bd_standard_shield_url]][bd_standard_url]

[bd_repo_url]: https://github.com/coz-repo/coz-logger
[bd_travis_url]: http://travis-ci.org/coz-repo/coz-logger
[bd_travis_shield_url]: http://img.shields.io/travis/coz-repo/coz-logger.svg?style=flat
[bd_travis_com_url]: http://travis-ci.com/coz-repo/coz-logger
[bd_travis_com_shield_url]: https://api.travis-ci.com/coz-repo/coz-logger.svg?token=
[bd_license_url]: https://github.com/coz-repo/coz-logger/blob/master/LICENSE
[bd_codeclimate_url]: http://codeclimate.com/github/coz-repo/coz-logger
[bd_codeclimate_shield_url]: http://img.shields.io/codeclimate/github/coz-repo/coz-logger.svg?style=flat
[bd_codeclimate_coverage_shield_url]: http://img.shields.io/codeclimate/coverage/github/coz-repo/coz-logger.svg?style=flat
[bd_gemnasium_url]: https://gemnasium.com/coz-repo/coz-logger
[bd_gemnasium_shield_url]: https://gemnasium.com/coz-repo/coz-logger.svg
[bd_npm_url]: http://www.npmjs.org/package/coz-logger
[bd_npm_shield_url]: http://img.shields.io/npm/v/coz-logger.svg?style=flat
[bd_standard_url]: http://standardjs.com/
[bd_standard_shield_url]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg

<!-- Badge End -->


<!-- Description Start -->
<a name="description"></a>

Logger for coz.

<!-- Description End -->




<!-- Sections Start -->
<a name="sections"></a>

<!-- Section from "doc/guides/01.Installation.md.hbs" Start -->

<a name="section-doc-guides-01-installation-md"></a>

Installation
-----

```bash
npm install coz-logger --save
```


<!-- Section from "doc/guides/01.Installation.md.hbs" End -->

<!-- Section from "doc/guides/02.Usage.md.hbs" Start -->

<a name="section-doc-guides-02-usage-md"></a>

Usage
----

```javascript
'use strict'

const cozLogger = require('coz-logger');

let logger = cozLogger({
  verbose: true
});

let startDate = new Date();
logger.infoStarted('render');
/*...*/
let endDate = new Date();
logger.infoFinished('render', startDate, endDate);
```

<!-- Section from "doc/guides/02.Usage.md.hbs" End -->


<!-- Sections Start -->


<!-- LICENSE Start -->
<a name="license"></a>

License
-------
This software is released under the [MIT License](https://github.com/coz-repo/coz-logger/blob/master/LICENSE).

<!-- LICENSE End -->


<!-- Links Start -->
<a name="links"></a>

Links
------

+ [coz][coz_url]

[coz_url]: https://github.com/coz-repo/coz

<!-- Links End -->
