### requirements_dev
* nose is for unittest
* pep8 is for PEP8 checks
* pyflake is for checking errors (latest version is 2.1.1)

### Troubleshooting
#### Mac OS X: ValueError: unknown locale: UTF-8 in Python
```
export LC_ALL=en_US.UTF-8
export LANG=en_US.UTF-8
```

### Tests Fixed (temporary)
* tests/test_commands.py

### Misc
**Running tests:**
```
nosetests -v tests/test_commands.py
```