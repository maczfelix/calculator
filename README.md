# calculator
<?php
    function calculator($num1, $num2, $operator) {
        switch ($operator) {
            case "+":
                return $num1 + $num2;
                break;
            case "-":
                return $num1 - $num2;
                break;
            case "*":
                return $num1 * $num2;
                break;
            case "/":
                return $num1 / $num2;
                break;
            default:
                return "Invalid operator";
        }
    }

    $num1 = 10;
    $num2 = 5;
    $operator = "+";
    echo calculator($num1, $num2, $operator);
?>
