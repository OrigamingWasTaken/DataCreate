# DataCreate

## What is this?

DataCreate is a python script made to generate datapacks from 1.13.3 up to 1.19.4

## Usage

### Python
`$ python3 DataCreate.py`

### Adding as a shell command

For exemple on Macos:
1. `$ mv DataCreate.py datacreate`
2. `$ chmod +x datacreate`
3. `$ sudo mv datacreate /usr/local/bin`

Reopen your terminal and you can now do `$ datacreate` to launch the program

## Troubleshooting

If the file doesn't work as a command, it is maybe because you don't have a symlink pointing to your python3. To fix this do:

`$ sudo ln -s $(which python3) /usr/local/bin/python3`

This will create a symlink to your python3
