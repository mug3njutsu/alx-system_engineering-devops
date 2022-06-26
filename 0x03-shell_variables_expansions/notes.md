```
Remove a path at the end of the $PATH variable -> PATH=$(sed -e "s/\:\<PATH>//" <<< $PATH)
```

