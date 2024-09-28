> Login to Jenkins Server using the link provide by DevOps Team.
> Install Git, Github and Custom Python Biulder modules.
> Go to source code management-->git-->URL. Here mention gitub URL where all the testing codes are stored.
> Create Pipeline by selecting home path for Python.exe file.
> Enter below commands at command section:  
    python -m venv env
    call /.venv/Scripts/activate.bat
    pip install selenium
    pip install pytest
    pip install openyxl
    pip install python-html
> Save the pipelie.
> Trigger the pipeline and it will execute all test cases and give HTML report.
