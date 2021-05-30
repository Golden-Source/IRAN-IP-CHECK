Hello , This code is for IP restriction of Iran for WHMCS modules.

To use this module do the following steps :

A ) Create a file named "checkiran.php" in the ("root/whmcs/modules/gateways/") folder
B ) Copy the code above into the "checkiran.php" File.
C ) Add the 
" 
require_once __DIR__ . "/checkiran.php";
    if(!golden_check_iran()){
        header("Location: ../../iran.php");
        exit();
    }
"
code patches within the main file of the payment module.

If you have an activation problem, send a request to our Telegram or site to fix your problem.
Site : Goldensource.ir
TeleGram : https://t.me/Golden_Support
