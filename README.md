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

## Setup
1. Clone thie repo.
2. Edit line 5 in rvcd file, change [your projects directory]
3. Open repo directoy in terminal
4. Make rvcd file executable by running 
    ```
    chmod u+x rvcd
    ``` 
    or open properties of rvcd file and make executable(under Permissions).
    
5. Move file to usr/bin by running 
    ```
    sudo mv rvcd /usr/bin
    ```

## Usage
Assuming you have a Gemfile and your gemset is named after your project, just type:
```
rvcd [project name]
```
If your gemset is named otherwise:
```
rvcd [project_name] [gemset_name]
```

