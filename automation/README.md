## Don't change Roboflow Notebooks list in README.md manually!

1. Add new notebook file `.ipynb` to `notebooks` directory.
2. Add new entry to `automation/notebooks-table-data.csv` file.
3. Run `automation/autogenerate_notebooks_table.py` script. Roboflow Notebooks table in `README.md` will update 
automatically. 

```bash
python3 automation/autogenerate_notebooks_table.py
```

4. Commit changes to feature branch. Create PR.