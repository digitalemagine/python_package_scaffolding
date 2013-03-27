Python package scaffolding (use it with echafaudage scaffolding engine https://github.com/harobed/echafaudage) 

Paste that at a Terminal prompt.

python -c "$(curl -fsSL https://raw.github.com/harobed/echafaudage/master/echafaudage.py)" -s https://github.com/harobed/python_package_scaffolding/archive/master.zip /tmp/my_new_project

Here, the scaffolding is installed in ``/tmp/my_new_project`` folder.

You can also set directly variable like that :

python -c "$(curl -fsSL https://raw.github.com/harobed/echafaudage/master/echafaudage.py)" -s https://github.com/harobed/python_package_scaffolding/archive/master.zip /tmp/my_new_project --vars package_name=my-package,author="Stéphane Klein",mail=contact@stephane-klein.info,version=0.1.0
