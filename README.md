```shell
$ hugo
Start building sites …
hugo v0.123.6+extended linux/amd64 BuildDate=unknown


                   | EN
-------------------+-----
  Pages            | 11
  Paginator pages  |  0
  Non-page files   |  0
  Static files     |  0
  Processed images |  0
  Aliases          |  2
  Cleaned          |  0

Total in 42 ms

$ hugo --minify
Start building sites …
hugo v0.123.6+extended linux/amd64 BuildDate=unknown

Total in 42 ms
Error: error building site: render: failed to render pages: failed to process "/posts/2024-02-27_reproducer/index.html": "/tmp/hugo-transform-error250503843:83:40": expected comma character or an array or object ending on line 83 and column 40
   12:     {
           ^
```
