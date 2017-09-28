pre-commit-cci
===

CircleCI hook to be used with http://pre-commit.com/

Validates the configuration using `circleci config validate`.  Requires the `circleci` binary.

## Usage

Add this to your `.pre-commit-config.yaml`

    - repo: git://github.com/pforman-driver/pre-commit-cci
      sha: master
      hooks:
        - id: cci-validate
