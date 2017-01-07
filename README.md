# ps-
ps备份脚本v1.0
/* ©HUIL 方便备份脚本 2017年1月7日*/
/*文件》脚本》脚本事件管理器》设置Photoshop事件触发动作，脚本选择本文件*/

var document = app.activeDocument; //当前文件
var fe = new File("E:\\设计\\设计备份\\备份.psd"); //备份后路径
var df = document.fullName;  //当前文件保存路径

document.fullName.copy(fe); //将当前文件拷贝到备份文件

