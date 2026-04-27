The bug was sum1 and sum2 are strings so they concatenate instead of adding.
You could fix t by converting num1 and num2 to numbers before they are added using Number().
