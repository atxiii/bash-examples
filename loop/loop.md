# Display only odd natural numbers from 1 to 30.

## Solutions:

1- With printf
```bash
printf "%s\n" {1..30..2}
```

2- With for ... in
```bash
for number in {1..30..2}
    do
    echo $number
    done
```
## Expected Output: 

```git
1
3
5
9
.
.
.
29
```