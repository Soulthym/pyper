# Pyper  
A python wrapper for session re-use, written in shell.  

## How to use?  
Once the process is running (with `./pyper` running),
a pipe is created (default is .pype).  
You can just pipe any text to the `.pype` file and it will run in the python shell  

### How to kill the process cleanly?  
Same prerequisites as "## How to use?" section  
Just pipe the command `KILL_PYPER` to the `.pype` file.  

## Example:  
```shell
./pyper &  
cat test.py > .pype  
echo "KILL_PYPER" > .pype  
```
