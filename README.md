python setup.py sdist bdist_wheel
python -m twine upload --skip-existing --repository testpypi dist/*

https://packaging.python.org/tutorials/packaging-projects/