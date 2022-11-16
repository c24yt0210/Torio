<?php
$arr = array(25, 47, 42, 56, 32);
$oddArray = array();
$evenArray = array();
echo "Orginal array: \n";
$size = count($arr);
for ($i = 0; $i < $size; $i++) {
    echo "$arr[$i] ";
}
$j = 0;
$k = 0;
for ($i = 0; $i < $size; $i++) {
    if ($arr[$i] % 2 == 0) {
        $evenArray[$j] = $arr[$i];
        $j++;
    } else {
        $oddArray[$k] = $arr[$i];
        $k++;
    }
}
echo "\nThe Even elements are : \n";
for ($i = 0; $i <= $j; $i++) {
    echo "$evenArray[$i] ";
}
echo "\nThe Odd elements are : \n";
for ($i = 0; $i <= $k; $i++) {
    echo "$oddArray[$i] ";
}
?>
