<h1 align="center">
  <br>
  <a href="https://github.com/s0md3v/XSStrike"><img src="https://image.ibb.co/cpuYoA/xsstrike-logo.png" alt="XSStrike"></a>
  <br>
  XSStrike
  <br>
</h1>

<h4 align="center">Advanced XSS Detection Suite</h4>

<p align="center">
  <a href="https://github.com/s0md3v/XSStrike/releases">
    <img src="https://img.shields.io/github/release/s0md3v/XSStrike.svg">
  </a>
  <a href="https://travis-ci.com/s0md3v/XSStrike">
    <img src="https://img.shields.io/travis/com/s0md3v/XSStrike.svg">
  </a>
  <a href="https://github.com/s0md3v/XSStrike/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues-closed-raw/s0md3v/XSStrike.svg">
  </a>
</p>

![multi xss](https://image.ibb.co/gOCV5L/Screenshot-2018-11-19-13-33-49.png)

<p align="center">
  <a href="https://github.com/s0md3v/XSStrike/wiki">XSStrike Wiki</a> •
  <a href="https://github.com/s0md3v/XSStrike/wiki/Usage">Usage</a> •
  <a href="https://github.com/s0md3v/XSStrike/wiki/FAQ">FAQ</a> •
  <a href="https://github.com/s0md3v/XSStrike/wiki/For-Developers">For Developers</a> •
  <a href="https://github.com/s0md3v/XSStrike/wiki/Compatibility-&-Dependencies">Compatibility</a> •
  <a href="https://github.com/s0md3v/XSStrike#gallery">Gallery</a>
</p>

*NOTE: this is a fork of the [original repo](https://github.com/s0md3v/XSStrike) refactored to create a xsstrike Python package*

See the original repo for documentation etc etc, only the installation / execution is modified here.

### Installation
Enter the following command in terminal:
```
pip install --user git+https://github.com/boffman/XSStrike.git
```
Or, using [pipx](https://github.com/pypa/pipx):
```
pipx install git+https://github.com/boffman/XSStrike.git
```

Now, XSStrike can be used at any time as follows:
```
xsstrike
```

### Documentation
See https://github.com/s0md3v/XSStrike

### FAQ
See https://github.com/s0md3v/XSStrike

### Gallery
See https://github.com/s0md3v/XSStrike

### Contribution, Credits & License
See https://github.com/s0md3v/XSStrike

Licensed under the GNU GPLv3, see [LICENSE](LICENSE) for more information.

The WAF signatures in `/xsstrike/db/wafSignatures.json` are taken & modified from [sqlmap](https://github.com/sqlmapproject/sqlmap). I extracted them from sqlmap's waf detection modules which can found [here](https://github.com/sqlmapproject/sqlmap/blob/master/waf/) and converted them to JSON.\
`/xsstrike/plugins/retireJS.py` is a modified version of [retirejslib](https://github.com/FallibleInc/retirejslib/).
