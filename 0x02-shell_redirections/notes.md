```
echo "\"" -> Prints one " character
echo 'abc'\''abc' -> Prints abc'abc
echo "abc"\""abc" -> Prints abc"abc
echo 'abc'"'"'abc' -> Prints abc'abc
echo "abc"'"'"abc" -> Prints abc"abc
echo -e "This is \x22\x27\x22\x27\x22text\x22\x27\x22\x27\x22" -> Prints This is "'"'"text"'"'"
echo "Hello"', world!' -> Prints Hello, world!
echo "I like to use" '"double quotes"' "sometimes" -> Prints I like to use "double quotes" sometimes

Exclude the current directory recursive -> find . -mindepth 1 -type d
Don't consider nested subdirectories (non-recursive search) -> find . -mindepth 1 -maxdepth 1 -type d
Recursive directory search -> ls -lR | grep ^d
Non-Recursive search -> ls -l | grep ^d
```
