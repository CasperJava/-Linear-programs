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
