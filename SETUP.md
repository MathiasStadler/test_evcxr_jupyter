# setup

## create new rust project

```bash
# go home
cd ~
# create new project folder and change inside
mkdir ./TEST_EVCXR_JUPYTER && cd $_

## install evcxr_jupyter

```bash
cargo install evcxr_jupyter

```

## add rustup component rust-src

```bash
rustup component add rust-src
```

## add ubuntu package jupyter-notebook

```bash
sudo apt install jupyter-notebook
```

## start jupyter notebook

```bash
jupyter notebook
```

## command for bash

```bash
grep  -v '^```.*' README.md |grep -v '.*```.*'|grep -v '^#.*'|grep .

```

## all command together

- grep  -v '^```.*' SETUP.md |grep -v '.*```.*'|grep -v '^#.*'|grep .

```bash
cd ~
mkdir ./TEST_EVCXR_JUPYTER && cd $_
cargo install evcxr_jupyter
rustup component add rust-src
sudo apt install jupyter-notebook
jupyter notebook
EOF
```
