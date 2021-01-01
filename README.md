# RVCD (Ruby Version Change Directory)

A simple bash script to replace 
```
cd project_name
rvm use 2.7.1@gemset
``` 
with
```
rvcd project
```

## Usage

1. Clone thie repo.
2. open directoy in terminal
3. make rvcd file executable by running 
    ```
    chmod u+x rvcd
    ``` 
    or open properties of rvcd file and make executable(under Permissions).
    
4. move file to usr/bin by running 
    ```
    sudo mv rvcd /usr/bin
    ```
4. Assuming you have a Gemfile and your gemset is named after your project, just type:
    ```
    rvcd [project name]
    ```
    If yor gemset is names otherwise:
    ```
    rvcd [project_name] [gemset_name]
    ```
