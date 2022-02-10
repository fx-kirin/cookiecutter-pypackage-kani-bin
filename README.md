cookiecutter-pypackage-kani
==============================


Usage
-----
    cd ~/.cookiecutters
    git clone https://github.com/fx-kirin/cookiecutter-pypackage-kani


Upload your project to Pypi.
-----

    pipreqs . --print | sed s/==.*// | > requirements.txt
    rm dist/*
    if [ -f README.md ]; then
        m2r README.md --overwrite
    fi
    python3 setup.py sdist
    twine upload --repository pypi dist/*

I recooment making bash script to do this.
