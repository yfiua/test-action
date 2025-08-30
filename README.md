# test-github-actions

This repository contains some GitHub Actions that can be manually run for test purposes.

* [action-fail](https://github.com/yfiua/test-github-actions/actions/workflows/action-fail.yml) will always fail
* [action-success](https://github.com/yfiua/test-github-actions/actions/workflows/action-success.yml) will always succeed
* [action-test-identity](https://github.com/yfiua/test-github-actions/actions/workflows/action-test-identity.yml) tests if the action is run from this exact repo; will succeed
* [action-test-no-identity] tests if the action is run from some other repo; will be skipped
