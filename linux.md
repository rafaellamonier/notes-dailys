## content to remeber about linux
### chmod

permissão total
```shell script
chmod +x nameFile.txt
```

flags de permissão
all can read/write/execute (full acess)
```shell script
chmod 777
```


owner can read/write/execute, group/others can read/execute.
```shell script
chmod 755 
```

owner can read/write, group/others can read only
```shell script
chmod 644 
```

grep by blocks, count lines begins of up
```shell script
cat fileName | grep -B [numbers line] "content search"
```

grep by blocks, count lines begins of down 
```shell script
cat fileName | grep -A [numbers line] "content search"
```
