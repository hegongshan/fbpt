### File batch processing tool (fbpt)

usage:

```shell
$ ./fbpt -h
usage: fbpt [-h]
            {classify,rename,create,mkdir,remove,write,copy,move,split,merge,chmod,find,check,deduplicate,md5,compress,encrypt,decrypt,convert}
            ...

File batch processing tool (fbpt)

positional arguments:
  {classify,rename,create,mkdir,remove,write,copy,move,split,merge,chmod,find,check,deduplicate,md5,compress,encrypt,decrypt,convert}
                        subcommand
    classify            Classify files into directory structure
    rename              Batch rename file
    create              Batch create file
    mkdir               Batch create directory
    remove              Batch remove file
    write               Batch write file
    copy                Batch copy file
    move                Batch move file
    split               Batch split file
    merge               Batch merge file
    chmod               Batch chmod
    find                Batch find
    check               Batch check
    deduplicate         Batch deduplicate
    md5                 Batch md5
    compress            Compress files based on entropy analysis
    encrypt             Batch encrypt files
    decrypt             Batch decrypt files
    convert             Batch convert files

options:
  -h, --help            show this help message and exit

```