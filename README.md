# php--function
PHP 函数
#  gmstrftime
gmstrftime("%H:%M:%S",3)  转化后 00:00:03

gmstrftime("%H:%M:%S",63)  转化后 00:01:03

#  final
PHP 5 新增了一个 final 关键字。如果父类中的方法被声明为 final，则子类无法覆盖该方法。如果一个类被声明为 final，则不能被继承。

# array_unshift();
语法array_unshift(array,value1,value2,value3...)
ex  
$a=array(0=>"red",1=>"green");
$b = array_unshift($a,"blue");
print_r($a); //输出   Array ( [0] => blue [a] => red [b] => green )
echo $b //输出3 

#  array_splice(array,start,length,array) 移除并取代

$a1=array("a"=>"red","b"=>"green","c"=>"blue","d"=>"yellow");
$a2=array("a"=>"purple","b"=>"orange");
array_splice($a1,0,2,$a2);
print_r($a1);  //输出  Array ( [0] => purple [1] => orange [c] => blue [d] => yellow )


