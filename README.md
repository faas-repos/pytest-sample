# Pytest Sample

## Fun Issues

I configured my python virtual environment using pyenv, pyenv-virtualenv and python 3.10.6. This was a mistake
as the OpenFaaS python3-flask template, appears to be using an older python 3.7 alpine image. I need to see if 
I can update this without issue. 

Symptoms - Jinja 3 is throwing errors because the template is using deprecated and removed methods. This causes the 
function to fail at startup.