# INFO
This dependency haven't receive updates for a long time a dartxx its not working for intl:0.18.0 obtaining this error => Because full_text_search >=0.8.0+3 depends on dartxx ^0.5.3+2 which depends on intl ^0.17.0, full_text_search >=0.8.0+3 requires intl ^0.17.0.

In this project I update dartxx for the people that use this package and need to update it.

# How to use it

```yaml
dependencies:
  full_text_search:
    git:
      url: https://github.com/Acuari0/full_text_search.git
      ref: master
```

# full_text_search

[![pub package](https://img.shields.io/pub/v/full_text_search.svg)](https://pub.dartlang.org/packages/full_text_search)
[![Coverage Status](https://coveralls.io/repos/github/SunnyApp/full_text_search/badge.svg?branch=master)](https://coveralls.io/github/SunnyApp/full_text_search?branch=master)

A package that performs in-memory full-text searching.  It doesn't maintain any indexes, but does support scoring
rules and tries to remain memory efficient.
