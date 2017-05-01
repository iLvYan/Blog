JSON:存储数据的方式

创建JSON对象
var gareen = {"name":"盖伦","hp":616}; 

访问JSON对象
gareen.name

创建JSON数组
var heros= 
[
    {"name":"盖伦","hp":616},
    {"name":"提莫","hp":313},
    {"name":"死哥","hp":432},
    {"name":"火女","hp":389}
]

访问JSON数组
heros[3].name

将JSON格式的字符串，转换为JSON对象
var gareen = $.parseJSON(s3);
var gareen = eval("("+s3+")");