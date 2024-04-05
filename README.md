Task-4:
1)// psvm(args)
public class App{
    public static void main(String[] args) throws Exception {
        System.out.println("Hello World!");
        
    }
}

Output:
Hello World!

2)//write without arg
public class App{
    public static void main(String[] ) throws Exception {
        System.out.println("Hello World!");
        
    }
}
Output:
"Syntax error, insert \"... VariableDeclaratorId\" to complete FormalParameterList",

3)spvm(args)
public class App{
    static public void main(String[] args) throws Exception {
        System.out.println("Hello World!");
        
    }
}

Output:
Hello World!

4)// psm(args)

public class App{
    static public  main(String[] args) throws Exception {
        System.out.println("Hello World!");
        
    }
}
output:
"Return type for the method is missing",
