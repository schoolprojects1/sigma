# Basic c++ Coding tool - lucas

#include <iostream>
#include <Windows.h>
#include <string>



    bool success = true; // or false depending on some condition

    if (success) {
        std::cout << " done " << std::endl;
        Sleep(1500);
        system("cls");
    } else {
        std::cout << " Program executed failed  " << std::endl;
        return 1;
    }

    return 0;
    
