Using pyinstaller on Mac OS with pyenv


Install python 3.10 with shared lib enabled

```
export CONFIGURE_OPTS="--enable-framework"
pyenv install -v 3.10-dev
```

Use the 3.10 python version 

```
pyenv shell 3.10-dev
```

Install pyinstaller through pip

```
pip install pyinstaller 
```

Compile 

```
pynstaller myscript.py
```

Launch

```
./dist/myscript/myscript
```
