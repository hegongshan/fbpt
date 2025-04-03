### File batch processing tool (fbpt)

usage:

```shell
$ ./fbpt -h
usage: fbpt [-h]
            {classify,rename,create,mkdir,remove,write,copy,move,split,merge,chmod,find,replace,name-check,integrity-check,permission-check,deduplicate,hash,compress,decompress,encrypt,decrypt,convert}
            ...

File batch processing tool (fbpt)

positional arguments:
  {classify,rename,create,mkdir,remove,write,copy,move,split,merge,chmod,find,replace,name-check,integrity-check,permission-check,deduplicate,hash,compress,decompress,encrypt,decrypt,convert}
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
    replace             Batch replace file content
    name-check          Batch file name check
    integrity-check     Batch file integrity check
    permission-check    Batch file permission check
    deduplicate         Batch deduplicate
    hash                Batch hash
    compress            Compress files based on entropy analysis
    decompress          Batch decompress files
    encrypt             Batch encrypt files
    decrypt             Batch decrypt files
    convert             Batch convert files

options:
  -h, --help            show this help message and exit
```

exmaples of using argument `convert`:

```shell
$ ./fbpt convert --src=./tests/srcPdf/ --dest=./tests/destDocx/ --type=pdf_to_docx
$ ./fbpt convert --src=./tests/srcDocx/ --dest=./tests/destPdf/ --type=word_to_pdf --wordapp=WPS

$ ./fbpt convert --src=./tests/srcImgs/ --dest=./tests/destPdf/ --type=imgs_to_pdf
Converted 4 images into a PDF file: ./tests/destPdf/img.001.pdf
```