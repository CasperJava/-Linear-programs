# -Linear-programs
// Задача № 1 
        // Найдите значение функции: z = ( (a – 3 ) * b / 2) + c.
        int a = 10;
        int b = 4;
        int c = 8;
        int z;
        z = ((a - 3) * b / 2) + c;
        System.out.println("Значение функции z= " + z);

// Задача № 2
        // Вычислить значение выражения по формуле 
        // (все переменные принимают действительные значения):
        // ((𝑏 +√(𝑏^2 + 4*𝑎*𝑐))/(2*а))-a^3*c+b^-2
        double a = 1;
        double b = 2;
        double c = 3;
        double d = Math.pow(b, 2) + 4 * a * c;
        double rezult;
        rezult = ((b + Math.sqrt(d)) / (2 * a))
                - (Math.pow(a, 3) * c) + Math.pow(b, -2);
        System.out.println("Значение выражения rezult= " + rezult);
        
// Задача № 3
        // Вычислить значение выражения по формуле 
        // (все переменные принимают действительные значения):
        // ((𝑠𝑖𝑛𝑥+𝑐𝑜𝑠𝑦)/(𝑐𝑜𝑠𝑥−𝑠𝑖𝑛𝑦))∗ 𝑡𝑔 (𝑥*𝑦)
        double x = 3.14;
        double y = 3.14;
        double rezult;
        rezult = ((Math.sin(x) + Math.cos(y)) / (Math.cos(x) - Math.sin(y)))
                * Math.tan(x * y);
        System.out.println("Значение выражения rezult= " + rezult);
        
// Задача № 4
        // Дано действительное число R вида nnn.ddd     
        // (три цифровых разряда в дробной и целой частях). 
        // Поменять местами дробную и целую части числа 
        // и вывести полученное значение числа.
        double r = 111.222;
        double x = (r * 1000) % 1000 + (int) r / 1000.0;
        System.out.println("Полученное значение = " + x);
