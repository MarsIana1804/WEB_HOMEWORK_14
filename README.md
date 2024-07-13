# WEB_HOMEWORK_14


# 1 - documentation - spinx
pip install sphinx sphinx-autodoc-typehints django

sphinx-quickstart

mkdir docs
cd docs

touch source/modules.rst

# docs
make html



# 2 - unittest

pip3 install pytest requests  

pip3 install fastapi uvicorn pytest httpx pytest-asyncio requests pytest-mock

pip3 install anyio
pip3 install pytest-asyncio
pip3 install pytest-tornasync
pip3 install pytest-trio
pip3 install pytest-twisted
pip3 install twisted

uvicorn test_main:app --reload

pytest

