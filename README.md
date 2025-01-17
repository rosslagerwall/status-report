# Developer Documentation for Xen-Bugtool

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=xenserver-next_status-report&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=xenserver-next_status-report)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=xenserver-next_status-report&metric=bugs)](https://sonarcloud.io/summary/new_code?id=xenserver-next_status-report)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=xenserver-next_status-report&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=xenserver-next_status-report)

This developer documentation provides detailed information about
the development environment for `xen-bugtool`,
a tool designed to assist with debugging XenServer issues.

For more information, see these README files:
- [README-python-install.md](README-python-install.md) - Preparing your
  Development VM for running the test suite
- [README-pytest.md](README-pytest.md) - Introduction on the recommended pytest suite for unit tests
- [README-pytest-chroot.md](README-pytest-chroot.md) - Introduction on the `pytest-chroot` test suite
- [README-Windows-WSL2.md](README-Windows-WSL2.md) - Windows and WSL2 setup tips
- [doc/pre-commit.md](doc/pre-commmit.md):
  Using `pre-commit` to run the test and static analysis checks locally
- [doc/coverage.md](doc/coverage.md): Introduction on **coverage** from `pytest`
