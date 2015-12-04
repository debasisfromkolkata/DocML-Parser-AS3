# DocML-Parser-AS3
use this library to parse docML
Example Usage::


var dc:docmlParser = new docmlParser();
var _file: File = new File();
 dc.parseDocml(_file,callBack);

function callBack(str:String){
	
	trace(str);
}
