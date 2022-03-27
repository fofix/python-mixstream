# Release notes

## 1.1.0 (2022-03-27)

- ci(tests): use pytest instead of setup.py test ([#32](https://github.com/fofix/python-mixstream/pull/32))
- feat(cython): add the language level to compiler directives ([#33](https://github.com/fofix/python-mixstream/pull/33))
- fix: remove `g_thread_init` (deprecation) ([#26](https://github.com/fofix/python-mixstream/pull/26))
- fix: replace `GStaticMutex` with `GMutex` (deprecation) ([#24](https://github.com/fofix/python-mixstream/pull/24))
- fix: replace `g_mutex_free` with `g_mutex_clear` to free resources (deprecation) ([#29](https://github.com/fofix/python-mixstream/pull/29))
- fix: replace `g_mutex_new` with `g_mutex_init` to init a mutex (deprecation) ([#28](https://github.com/fofix/python-mixstream/pull/28))

## 1.0.0 (2022-03-03)

- feat: build extension with scikit-build

## 0.0.1 (2021-06-05)

Initial release. Extracted from FoFiX / fretwork.
