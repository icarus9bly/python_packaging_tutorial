# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

# Develop this module
- Steps to follow:
```python
# cd /path/to/python_packaging_tutorial
python3 -m build
python3 -m twine upload --repository testpypi dist/*CurrentVersion* --verbose
# python3 -m twine upload --repository testpypi dist/*0.0.4* --verbose
```
