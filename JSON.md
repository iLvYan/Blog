JSON:�洢���ݵķ�ʽ

����JSON����
var gareen = {"name":"����","hp":616}; 

����JSON����
gareen.name

����JSON����
var heros= 
[
    {"name":"����","hp":616},
    {"name":"��Ī","hp":313},
    {"name":"����","hp":432},
    {"name":"��Ů","hp":389}
]

����JSON����
heros[3].name

��JSON��ʽ���ַ�����ת��ΪJSON����
var gareen = $.parseJSON(s3);
var gareen = eval("("+s3+")");