```
echo "\"" -> Prints one " character
echo 'abc'\''abc' -> Prints abc'abc
echo "abc"\""abc" -> Prints abc"abc
echo 'abc'"'"'abc' -> Prints abc'abc
echo "abc"'"'"abc" -> Prints abc"abc
echo -e "This is \x22\x27\x22\x27\x22text\x22\x27\x22\x27\x22" -> Prints This is "'"'"text"'"'"
echo "Hello"', world!' -> Prints Hello, world!
echo "I like to use" '"double quotes"' "sometimes" -> Prints I like to use "double quotes" sometimes
```
