# simple_semver 

## Usage

    go get github.com/csjewell/simple_semver

## Version format:

The versions implemented by `simple_semver` module are a subset of the ones described in [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html). They can begin with a v or not, and must have major, minor, and patch levels. After the patch level, they can have an optional release-state-modifier of `-alpha.#`, `-beta.#`, `-gamma.#`, or `-rc.#`, where # increases from 1. In addition, versions can have a "pre-release marker" of `-pre`, indicating that the version is a prerelease of what is otherwise specified.

Examples:

    v1.0.1
    2.5.0
    0.2.1-alpha.1
    v0.2.1-pre
    1.4.9-rc.16-pre

