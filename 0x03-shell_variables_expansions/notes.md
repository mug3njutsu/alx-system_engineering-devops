```
Remove a path at the end of the $PATH variable -> PATH=$(sed -e "s/\:\<PATH>//" <<< $PATH)
Convert binary to decimal -> echo "$((2#101010101))"
Convert binary to hexadecimal -> printf '%x\n' "$((2#101010101))"
```
