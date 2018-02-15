# contao_quick_install

This is a compact ruby command line script which installs Contao 4 and the following rocksolid plugins:

1. madeyourday/contao-rocksolid-columns 
2. madeyourday/contao-rocksolid-custom-elements
3. madeyourday/contao-rocksolid-slider
4. madeyourday/contao-rocksolid-frontend-helper

Feel free to costumize this script.

# Troubleshooting
If the script is not working, check the followings:

- Check the variable `path_to_php`. It must direct to the PHP of the server


## Inputs and syntax

```
contao_version
```

Usually strings like `4.5`, `3.4.5` or `4.5.*`

```
directory
```
Given that your SSH access is pointing on root /, you need to specify where contao should be installing. Usually it's the directory of the website like `mywebsite`, or `abc.de`


```
host
```
Type in your SSH host. 

```
user
```
Type in your SSH user. 

```
passowrd
```
Type in your SSH password. 
