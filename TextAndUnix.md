Split every line by space and get fields from it
```sh
$  cut -f 1 input.txt > output.txt
```
Split a file into two or more smaller files
```sh
$  split -l 100 input.txt new
```
Add space to beginning of line
```sh
$  awk '{print " "$0}' input.txt > output.txt
``` 