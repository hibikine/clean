# Clean.py

[![Build Status](https://travis-ci.org/HibikineKage/clean.svg?branch=master)](https://travis-ci.org/HibikineKage/clean) [![Coverage Status](https://coveralls.io/repos/github/HibikineKage/clean/badge.svg?branch=master)](https://coveralls.io/github/HibikineKage/clean?branch=master) [![PEP8](https://img.shields.io/badge/code%20style-pep8-orange.svg)](https://www.python.org/dev/peps/pep-0008/) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/HibikineKage/clean/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/HibikineKage/clean/?branch=master) [![Code Intelligence Status](https://scrutinizer-ci.com/g/HibikineKage/clean/badges/code-intelligence.svg?b=master)](https://scrutinizer-ci.com/code-intelligence) [![Dependency Status](https://www.versioneye.com/user/projects/5ab5f5a60fb24f0ac49c2b9e/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/5ab5f5a60fb24f0ac49c2b9e) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/91755cd5aab24d07bc707d85a97a2d96)](https://www.codacy.com/app/HibikineKage/clean?utm_source=github.com&utm_medium=referral&utm_content=HibikineKage/clean&utm_campaign=Badge_Grade)

Glob files sorter

## Usage

Please type `clean.sh --help`

```bash
$ clean.sh cwd
/home/kage/

$ clean.sh add foo*.txt ~/bar
$ clean.sh list
foo*.txt => ~/bar

$ clean.sh run
/home/kage/foo1.txt => ~/bar/foo1.txt
/home/kage/foo2.txt => ~/bar/foo2.txt
/home/kage/foobar.txt => ~/bar/foobar.txt

$ cat ~/.cleanrc
{
    "path": [{"path": "~/bar", "glob": "foo*.txt"}]
}
```

## License

MIT
