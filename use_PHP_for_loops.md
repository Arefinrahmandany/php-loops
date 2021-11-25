//Create a loop where the initial value is 10000. You need to rotate the loop 50 times and use the increment and decrement operator twice.
<?php
for($i=10000; $i >= 9950; $i--){
                    echo "{$i}<br>";
                }
                ?>
            
                <?php
                for($i=10000; $i <= 10050; $i++){
                    echo "{$i}<br>";
                }
                ?>
  
  // Create a loop that rotates 500 times using the for loop where you just pull out the numbers divisible by 3 and 4.
  <?php
                    for($i=1; $i <= 500; $i++){
                    if($i % 3 == 0){
                        echo "{$i}<br>";
                    }
                }
                ?>
  
  <?php
                    for($i=1;$i<=500;$i++){
                    if($i % 4 == 0){
                        echo "{$i}<br>";
                    }
                }
                ?>
  
  //Create a loop using for loop that will increment by 3 per step and the loop will break the auto loop when it finds a number divisible by 11 (end the loop).
  <?php
                for( $i=1; $i <= 100; $i = $i+3){
                    echo "{$i} <br>";
                    if($i % 11 == 0){
                        break;
                    }
                }
                ?>
  
  //Think about using the loop and find out the number of 2,3,4,5
  <?php
                for($i=1;$i<=50;$i++){
                    if($i % 5 == 0){
                        echo "{$i}<br>";
                    }
                }
                ?>
  
  <?php
                for($i=4;$i<=40;$i+=4){
                    echo "{$i}<br>";
                }
                ?>
  
  <?php
                for($i=3;$i<=30;$i+=3){
                    echo "{$i}<br>";
                }
                ?>
  
  <?php
                for($i=2;$i<=20;$i+=2){
                    echo "{$i}<br>";
                }
                ?>
  
  //Prepare a loop where the loop will be multiplied by 6 per step and the loop will stop whenever it gets a number divisible by 5.
  
  <?php
                for( $i=1; $i <= 100; $i = $i+6){
                    echo "{$i} <br>";

                    if($i % 5 == 0){
                        break;
                    }
                }
                ?>
