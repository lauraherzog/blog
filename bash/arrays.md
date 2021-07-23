# BASH and arrays

## Declare an array

```
# this is a non associative array
declare -a ARRAY
```

## Add items to non associative array

```
ARRAY=("${ARRAY[@]}" "${ITEM}")
```
