```c
#include <stdio.h>

struct Bio {
    char* name;
    char* major;
    char* university;
    char* base;
};

struct Stack {
    char* languages[3];
    char* databases[1];
    char* ongoing[2];
};

struct Social {
    char* Discord;
    char* Instagram;
};

int main() {
    struct Bio bio = {
        name = "Dzaki Sultan Rabbani";
        major = "Informatics";
        university = "Universitas Negeri Padang";
        base = "Padang, Indonesia";
    };

    struct Stack stack = {
        languanges = {"HTML", "CSS", "C"};
        databases = {"NULL"};
        ongoing = {"JAVA", "PYTHON"};
    };

    struct Social social = {
        Discord = "NyotNyot";
        Instagram = "dzakisultanr";
    };

    return 0;
}

```
