# Single-Chip_Document
单片机文档学习整理
/*这段代码用于检测按键相对比较清晰，可靠性高，可以作为通用模板。*/
key = KEY_NULL;
while(key == KEY_NULL)
{
key = keyscan();
switch(key)
 {
... ...
 }
}
