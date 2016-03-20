# what is this?

This is the tools for move data from Redis to Spark use Pyspark

# how use?
redis keys like:
>li9t209jm7mc6m4vmn88o5a7j0:1433138813.8056:55.55.55.22:yahoo:0
>li9t209jm7mc6m4vmn88o5a7j0:1433138813.8056:55.55.55.22:google:0
>li9t209jm7mc6m4vmn88o5a7j0:1433138813.8056:55.55.55.22:baidu:0


the KEY is zset type, the values of the KEY just like
>shell> ZRANGE li9t27mskklc769vmn88o5appp:1433138814.0488:10.10.10.29:360:0 0 -1
><br />"www.xxxxx.com/help/999"
><br />"www.xxxxx.com"
><br />"www.xxxxx.com/member/xxx"
><br />"www.xxxxx./com/kkki"
><br />"www.xxxxxx..com/goods/list/1020"
><br />"www.xxxxx.com/yyyy"

this tools will make two tables for the data above. tables has relationship



