# Readme

A tool to help you convert javascript object to json on command line.

## Usage:

```bash
$ echo "{a: 10, b: 20, name: 'sahil'}" | obj-json
# Output: {"a":10,"b":20,"name":"sahil"}
```

- FYI: NOW I CAN USE `jq` AS WELL:

```bash
$ echo "{a: 10, b: 20, name: 'sahil'}" | obj-json | jq
# Output:
{
  "a": 10,
  "b": 20,
  "name": "sahil"
}
```
