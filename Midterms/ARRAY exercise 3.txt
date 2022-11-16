<?php
echo "Test Data\n"."Number of elements to be stored in the array = 3" ;

$input= array(5,1,1);

$count_values = array();
foreach ($input as $a) {

     @$count_values[$a]++;

}
echo "\nExpected Output:";
print_r($count_values);
echo "\nTotal number of duplicate elements found in the array is : ".count($count_values);
?>