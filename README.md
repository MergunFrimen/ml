# ML project

Machine learning project about weather forecast.

## Requirements

- Python 3
- VSCode (optional)

## How to run project

### VSCode

1. Create a virtual environment and install dependencies

```bash
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install --upgrade pip
$ pip install -r requirements.txt
```

2. Run this command to strip notebook output cells from commits

```bash
(venv) $ nbstripout --install
```

3. Go to [notebook.ipynb](./src/notebook.ipynb) and select the kernel from the dropdown menu

```text
Select Kernel -> Python Environments... -> venv
```

**OR** run jupyter notebook in browser

```bash
(venv) $ jupyter notebook
```

and then use the server kernel

```text
Select Kernel -> Select Another Kernel... -> Existing Jupyter Server... -> JUPYTER_NOTEBOOK_URL
```

### Browser

To run the project in a browser, you can run the following command

```bash
(venv) $ jupyter notebook
```

Then open the notebook in the browser at [http://localhost:8888/notebooks/src/notebook.ipynb](http://localhost:8888/notebooks/src/notebook.ipynb).

## Pip dependencies

If you want to add new dependencies, you can do it by running

```bash
$ pip install <package>
$ pip freeze > requirements.txt
```

Don't forget to commit the changes.

## Authors

- [**@denbalogh**](https://github.com/denbalogh)
- [**@MergunFrimen**](https://github.com/MergunFrimen)
- [**@honza: TODO**](https://github.com/TODO)


## License

MIT
