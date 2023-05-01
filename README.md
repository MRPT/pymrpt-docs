# pymrpt-docs
pydoc for pymrpt bindings



## Regenerate docs

    # build pymrpt locally
    # ...

    export PYTHONPATH=/home/jlblanco/code/mrpt/build-Release
    cd docs && ~/code/mrpt/python/build-pydocs-from-local-build.sh

    # overwrite
    git commit -a --amend
    git push --force
