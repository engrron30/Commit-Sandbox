
# Printing in C

First step is we use the *#include* keyword. This keyword indicates that we are going to call some libraries built in C. These libraries are already with C packages whenever you downloaded it in your system.

    #include <stdio.h>

Define your main function. This is the entry point of the code whenever it is executed.

     int main()
     {

     }

To do printing characters in C, we can use the *printf* keyword which is called inside the *stdio* library we have imported before. Add a printf line inside the main function with the characters you want to see in your terminal.

    int main()
    {
        printf("Hello World!");
    }

Notice that our main function has some *int* keyword when it is defined. This means when the function is called or has exited, it will return an integer value. In this case, we need to define a returning integer when this main function is done using *return* keyword. We can use 0 to indicate that our main function is successful and done.

    int main()
    {
        printf("Hello World!);
        return 0;
    }
