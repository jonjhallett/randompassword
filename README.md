# Generate random passwords

A simple script to generate random passwords using randomness from
/dev/urandom. The script defaults to a 43-character password, which is
equivalent to 256 bits of entropy, but you can specific the number of
characters as an argument. The passwords contain only alphanumeric
characters.

```
$ randompassword 22
7Vy4GVeXmw9DNr63C9j23V
```
