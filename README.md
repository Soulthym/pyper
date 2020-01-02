# Pyper  
A python wrapper for session re-use, written in shell.  

## How to use?  
just pipe any text to the `.pype` file.  

### How to kill the process cleanly?  
just pipe the command `KILL_PYPER` to the `.pype` file.  

## Example:  
```shell
./pyper &  
cat test.py > .pype  
echo "KILL_PYPER" > .pype  
```
