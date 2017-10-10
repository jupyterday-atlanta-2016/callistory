
# Callistory

`callistory` is a reusable project to assist creating DIY technology events.  This project will prototype the first Callisto Morn event in Atlanta, Georgia on November 11.

# Build

All build logic is contained with in the `readme.ipynb` file.  Use `nbconvert` to execute this notebook with the command below.

    !jupyter nbconvert --inplace --execute --to notebook readme.ipynb


```python
    !jupyter nbconvert --to markdown about.ipynb readme.ipynb
    !jupyter nbconvert --execute --TemplateExporter.exclude_input=True --TemplateExporter.exclude_input=True index.ipynb 
```


    !jupyter nbconvert --to markdown about.ipynb readme.ipynb
    !jupyter nbconvert --execute --TemplateExporter.exclude_input=True --TemplateExporter.exclude_input=True index.ipynb 


    [NbConvertApp] Converting notebook about.ipynb to markdown
    [NbConvertApp] Writing 449 bytes to about.md
    [NbConvertApp] Converting notebook readme.ipynb to markdown
    [NbConvertApp] Writing 2158 bytes to readme.md
    [NbConvertApp] Converting notebook index.ipynb to html
    [NbConvertApp] Executing notebook with kernel: python3
    [NbConvertApp] Writing 256941 bytes to index.html



```python
# Development

See __[contributing.ipynb](contributing.ipynb)__ for more details.

* __[readme.ipynb](readme.ipynb)__ provides instruction for external services.
* __[about.ipynb](about.ipynb)__ provides information about the event.  Who what where when how why.
* __[long.ipynb](long.ipynb)__ provides provides long format presentations information.
* __[short.ipynb](short.ipynb)__ provides provides short format presentations information.
* __[participants.ipynb](participants.ipynb)__ provides extra information about the conference participants.
* __[code_of_conduct.md](code_of_conduct.md)__
```


# Development

See __[contributing.ipynb](contributing.ipynb)__ for more details.

* __[readme.ipynb](readme.ipynb)__ provides instruction for external services.
* __[about.ipynb](about.ipynb)__ provides information about the event.  Who what where when how why.
* __[long.ipynb](long.ipynb)__ provides provides long format presentations information.
* __[short.ipynb](short.ipynb)__ provides provides short format presentations information.
* __[participants.ipynb](participants.ipynb)__ provides extra information about the conference participants.
* __[code_of_conduct.md](code_of_conduct.md)__



```python
    %%file custom.css
    .output code {display: none;}
```


    %%file custom.css
    .output code {display: none;}


    Overwriting custom.css
