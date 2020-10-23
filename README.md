# SauronEye-Modify

在原基础上加上将找到的文件压缩打包上传oss

```
SauronEye.exe -h

         === SauronEye Modify by Uknow  ===

Usage: SauronEye.exe [OPTIONS]+ argument
Search directories for files containing specific keywords.

Options:
  -d, --directories=VALUE    Directories to search
  -f, --filetypes=VALUE      Filetypes to search for/in
  -k, --keywords=VALUE       Keywords to search for
  -o, --osskey=VALUE         aliyunOSS key
                                format: bucketName:accessKeyId:accessKeySecret:
                               endpoint
  -c, --contents             Search file contents
  -m, --maxfilesize=VALUE    Max file size to search contents in, in kilobytes
  -b, --beforedate=VALUE     Filter files last modified before this date,
                                format: yyyy-MM-dd
  -a, --afterdate=VALUE      Filter files last modified after this date,
                                format: yyyy-MM-dd
  -s, --systemdirs           Search in filesystem directories %APPDATA% and %
                               WINDOWS%
  -v, --vbamacrocheck        Check if 2003 Office files (*.doc and *.xls)
                               contain a VBA macro
  -h, --help                 Show help
  ```
