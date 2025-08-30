# test-github-actions

This repository contains some GitHub Actions that can be manually run for test purposes.

* [action-fail](https://github.com/yfiua/test-github-actions/actions/workflows/action-fail.yml) will always fail
* [action-success](https://github.com/yfiua/test-github-actions/actions/workflows/action-success.yml) will always succeed
* [action-test-identity](https://github.com/yfiua/test-github-actions/actions/workflows/action-test-identity.yml) tests if the action is run from this exact repo; will succeed
* [action-test-no-identity](https://github.com/yfiua/test-github-actions/actions/workflows/action-test-no-identity.yml) tests if the action is run from some other repo; will be skipped
* [action-update-timestamp](https://github.com/yfiua/test-github-actions/actions/workflows/action-update-timestamp.yml) updates the timestamp on [GitHup Pages](https://yfiua.github.io/test-github-actions/)
