# enigma2-note

/web/timerchange?sRef=1%3A0%3A2%3A37%3AB%3A4080%3A40000%3A0%3A0%3A0%3A&begin=1512403200&end=1512421260&name=&description=&dirname=%2Fmedia%2Fhdd%2F&tags=&afterevent=3&eit=0&disabled=0&justplay=0&repeated=125&channelOld=&beginOld=0&endOld=0&eventID0&deleteOldOnSave=0

/web/timerlistwrite?write=saveWriteNow

var xmldoc=loadXML(text.xml)
var elements = xmlDoc.getElementsByTagName("Company");
for (var i = 0; i < elements.length; i++) {
  var name = elements[i].getElementsByTagName("cNname")[0].firstChild.nodeValue;
  var ip = elements[i].getElementsByTagName("cIP")[0].firstChild.nodeValue;               
}

## 接口文档 (Eng)
http://dream.reichholf.net/wiki/Enigma2:WebInterface

## 接口URL
信息
http://192.168.0.2/web/about  
http://192.168.0.2/web/deviceinfo  
保存位置
http://192.168.0.2/web/getcurrlocation  
音量
http://192.168.0.2/web/vol?set=down  

## OSCAM位置
ftp://192.168.0.2/etc/tuxbox/config/oscam.server  
