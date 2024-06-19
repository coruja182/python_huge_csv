# python_huge_csv

python huge csv

## Environment Setup

```shell
python -m venv .venv

# linux or macos
source .venv/bin/activate

# windows
.venv\bin\Activate.ps1
```

## Windows Troubleshooting

Note On Microsoft Windows, it may be required to enable the Activate.ps1 script by setting the execution policy for the user.
You can do this by issuing the following PowerShell command:

```shell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

## Reference

- Splitting huge CSV into smaller ones: <https://blog.finxter.com/5-best-ways-to-split-a-csv-into-multiple-files-using-python-pandas/>
- Create a folder if it does not exist already <https://stackoverflow.com/questions/32123394/workflow-to-create-a-folder-if-it-doesnt-exist-already>
- Download a file from a URL <https://realpython.com/python-download-file-from-url/>
- Concatenate multiple CSV using pandas <https://stackoverflow.com/questions/20906474/import-multiple-csv-files-into-pandas-and-concatenate-into-one-dataframe>
- VENV creation of virtual environments <https://docs.python.org/3/library/venv.html>
