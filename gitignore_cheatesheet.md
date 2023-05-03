
| pattern   | Explanation | examples |
|-----------|-------------|----------|
| # text comment|Lines starting with # are ignored  |  |
| lib/name.file   | Patterns specifiing files in specific folders are always realative to root (even if you do not start with / )  | /lib/name.file   |
| **/name | All name folders, and files and folders in any name folder | /name/log.file |
|  *.file    | All files withe .file extention    |    /name.file    |
|  name?.file    |   ? matches a single non-specific character     |    /names.file  |
|  /lib/**/name   |  All name folders, and files and folders in any name folder within the lib folder.   |  /lib/name/log.file    |