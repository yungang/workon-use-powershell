# workon-use-powershell
use virtualenvwrapper-win workon by powershell 7

# install
copy workon.ps1 and cdproject.ps1 file to your {python install dir}/Scripts/
and add {WORKON_HOME} environment variable, eg:{D:\python-venv} 

# usage
```
mkvirtualenv -a path-to-your-project test
deactivate
workon test
cdproject test
```