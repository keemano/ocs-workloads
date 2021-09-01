# OCS-CI

OCS CI is a framework to test Red Hat OCS features and functionality using AWS
and other supported platforms. The framework is based on pytest.

## Automatically generated documentation

The primary documentation is available at
[ocs-ci.readthedocs.io](https://ocs-ci.readthedocs.io/en/latest/).

Source files of the documentation are maintained as a
[Sphinx](https://www.sphinx-doc.org/en/master/) project in [`docs`
directory](docs/).

## License

This project is open sourced under MIT License.
# Repo consumed by https://github.com/red-hat-storage/ocs-ci

Repo will contain workload files to setup

- AMQ
- Couchbase
- Logging
- ECK
    This is the elastic search deployment files.
    
    The yaml files was pulled from : https://download.elastic.co/downloads/eck/<version\>/
    
    The current version is 1.7.1, this version is the supported one for k8s 1.22
    
    to deploy on k8s before 1.16 the *-legacy.yaml files need to be used.
