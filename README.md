# lauzhack2022

---

## Environment Setup

### Create Fresh

```shell
conda create -n lauzhack ipykernel notebook jupyterlab numpy pandas scipy matplotlib scikit-learn pytorch

pip install streamlit
```

### Create

```shell
conda env create -n lauzhack --file environment.yml
```

### Export

```shell
conda env export lauzhack>environment.yml
```

---

## Run Streamlit

```shell

streamlit run src/streamlit_test.py
```

