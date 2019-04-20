[Server]
; 标题|服务器标题|服务器名称|服务器IP|服务器端口|是否自动展开(0不展开，1自动展开)|微端IP|微端端口(0表示不使用微端)|安全盾防火墙端口(0表示不使用防火墙)|防火墙类型，0=安全盾防火墙 1=风盾 2=恶魔盾
0=电信服务器|热血传奇7008|传奇归来7008|127.0.0.1|7008|1|127.0.0.1|0|0
1=电信服务器|传奇归来7000|传奇归来7000|127.0.0.1|7000|1|127.0.0.1|0|0
2=网通服务器|热血传奇7008|传奇归来7008|127.0.0.1|7008|1|127.0.0.1|0|0
3=网通服务器|传奇归来7000|传奇归来7000|127.0.0.1|7000|1|127.0.0.1|0|0
[Setup]
公告地址=http://www.mirgom.com
官方首页=http://www.mirgom.com
客户服务=http://www.mirgom.com

刷新速度=360
;时间秒，参数不小于30

自动刷新=0
;0不自动刷新 1自动刷新

自动选择游戏区=电信服务器|传奇归来7000|传奇归来7000

;增加这里的输入前面三个名称，登录器打开就会自动选择这个区，如果只输入“电信服务器”就会自动展开“电信服务器”这一项
;例如：自动选择游戏区=电信服务器 就会自动展开“电信服务器” 输入完整的前面三个名称就会自动选择这个区
;为空时，当然就不会自动选择任何区。


[Upgrade]
;------------------------------------------------------------------------------------------------------------------------------
;------------------------------------------------------------------------------------------------------------------------------
;------------------------补丁自动更新配置演示，如果没有补丁更新的，请把以下的内容全部删除--------------------------------------
;------------------------------------------------------------------------------------------------------------------------------
;------------------------补丁的MD5值获取方法：把补丁拖动到登陆器配置器上就可以-------------------------------------------------
;------------------------------------------------------------------------------------------------------------------------------
;------------------------------------------------------------------------------------------------------------------------------
;类型(0=普通文件  1=更新登录器本身时必须是exe文件  2=zip压缩文件)     保存目录(更新登录器本身时目录名称使用\斜杠)     文件名称     MD5值     下载地址
;登录器自身的更新，有的空间可能不支持扩展名为“.exe”文件的下载，可以把扩展名称改成“.rar”这样就可以下载了，注意不是压缩成rar格式，而是直接把“.exe”扩展名称修改成“.rar”

0=1     \     GameOfMir_登录器.exe     6cb5a722f54ed491ca4fddd0a507332d     http://www.mirgom.com/GameOfMir_登录器.exe
1=2     Data     data.zip     fdc49e06560f62ddbc5c178d3c02b736     http://www.mirgom.com/data.zip
2=2     Map     Map.zip     fdc49e06560f62ddbc5c178d3c02b736     http://www.mirgom.com/Map.zip
3=2     Wav     Wav.zip     fdc49e06560f62ddbc5c178d3c02b736     http://www.mirgomr.com/Wav.zip
4=2     Resources\Data     Resdata.zip     fdc49e06560f62ddbc5c178d3c02b736     http://www.mirgom.com/Resdata.zip
5=2     Resources\Map     ResMap.zip     fdc49e06560f62ddbc5c178d3c02b736     http://www.mirgom.com/ResMap.zip
6=2     Resources\Wav     ResWav.zip     fdc49e06560f62ddbc5c178d3c02b736     http://www.mirgom.com/ResWav.zip
7=2     Resources\Graphics\Human     Human.zip     fdc49e06560f62ddbc5c178d3c02b736     http://www.mirgom.com/Human.zip
