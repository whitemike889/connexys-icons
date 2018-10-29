# ![connexys-icons](banner.png)

> This repository contains the icon fonts maintained by Bullhorn.

---
 
 [![Build Status](https://travis-ci.org/bullhorn/connexys-icons.svg?branch=master)](https://travis-ci.org/bullhorn/connexys-icons?branch=master)
 [![npm version](https://badge.fury.io/js/%40bullhorn%2Fconnexys-icons.svg)](https://badge.fury.io/js/%40bullhorn%2Fconnexys-icons)
 [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
 [![built by](https://img.shields.io/badge/built%20by-bullhorn-f39f37.svg)](https://bullhon.github.io/connexys-icons)

---

[Website](http://bullhorn.github.io) • [Preview](http://bullhorn.github.io/connexys-icons) • [Blog](https://medium.com/bullhorn-dev) 


## Install

Available via npm

```bash
npm install --save @bullhorn/connexys-icons
```


## Usage

### Loading the Styles

> Import from CDN

```html
/* UnPkg for NPM Version*/
<link rel="stylesheet" type="text/css" href="//unpkg.com/@bullhorn/connexys-icons@0.0.0/fonts/ConnexysIcons.css"/>
/* RawGit for GitHub Version*/
<link rel="stylesheet" type="text/css" href="//cdn.rawgit.com/bullhorn/connexys-icons/v0.0.0/fonts/ConnexysIcons.css"/>
```

> Import via scss

```scss
@include 'connexys-icons';
```

### Using an icon

<p>
    <img title="Candidate icon" src="http://cdn.rawgit.com/bullhorn/connexys-icons/master/icons/candidate.svg" width="64" />
    <img title="Job icon" src="http://cdn.rawgit.com/bullhorn/connexys-icons/master/icons/jobs.svg" width="64" />
    <img title="Submission icon" src="http://cdn.rawgit.com/bullhorn/connexys-icons/master/icons/job-application.svg" width="64" />
    <img title="Browse icon" src="http://cdn.rawgit.com/bullhorn/connexys-icons/master/icons/browse.svg" width="64" />
</p>

```html
<i class="icon-candidate"></i>
<i class="icon-persjobson"></i>
<i class="icon-job-application"></i>
<i class="icon-browse"></i>
```
## Contributing

Please read through our [contributing guidelines](https://github.com/bullhorn/connexys-icons/blob/master/CONTRIBUTING.md).
Included are directions for opening issues, coding standards, and notes on development.

## Versioning

Maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered
with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions, including new icons, without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes, changes to brand logos, and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org.

---

<p>
	<img src="bully.png" align="left" width="24" />
	<span>&nbsp; Built by Bullhorn, copyright (c) forever</span>
</p>
