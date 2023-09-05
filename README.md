# RSECon23 walkthrough on Pydra

Deploy the notebook environment:

```shell
$ conda-lock install -p ./.venv
```

Activate the environment:

```shell
$ conda activate ./.venv
```

Generate the HTML slides:

```shell
$ jupyter nbconvert --to slides presentation.ipynb
```