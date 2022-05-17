# Subscan Plugin


The subscan plugin is an interface lib to [subscan-essentials](https://github.com/yspk/subscan-essentials) plugin, and [Gen](https://github.com/yspk/subscan-plugin/tree/master/tools) tool can automatically generate plugin templates

## Install

```
go get github.com/yspk/subscan-plugin
```

## Usage

[tutorial](/tutorial.md)

## Test

```shell script
go test ./... -v
cd tools/gen-plugin && ./test_gen_tools.sh
```

## LICENSE

GPL-3.0

## Resource
 
- [subscan-essentials] https://github.com/yspk/subscan-essentials
- [substrate-api-rpc] https://github.com/yspk/substrate-api-rpc
