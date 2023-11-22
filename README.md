```c
#include <stdio.h>

struct Bio {
    char* name;
    char* major;
    char* university;
    char* base;
};

struct Stack {
    char* languages[2];
    char* databases[1];
    char* ongoing[3];
};

struct Social {
    char* discord;
    char* instagram;
};

int main() {
    struct Bio bio = {
        .name = "Dzaki Sultan Rabbani",
        .major = "Informatics",
        .university = "Universitas Negeri Padang",
        .base = "Padang, Indonesia"
    };

    struct Stack stack = {
        .languages = {"HTML", "CSS"},
        .databases = {NULL},
        .ongoing = {"C", "JAVA", "PYTHON"}
    };

    struct Social social = {
        .discord = "NyotNyot",
        .instagram = "dzakisultanr"
    };

    return 0;
}

```
