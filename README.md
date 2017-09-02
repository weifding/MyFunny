MyFood
======
Log.PHP用法

require_once "log.php";

$logHandler = new CLogFileHandler(date('Y-m-d').'.log');

$log = Log::Init($logHandler,15);

Log::INFO("My Food");   
