<img src="https://github.com/user-attachments/assets/db5b96e8-70a7-4de5-92fe-8c6fee689adb" width="1000" height="auto" alt="GIF description">


# prox@sec ~ $ whoami
```C
#include <stdio.h>
#include <stdbool.h>

typedef struct s_prox {
    char *name;
    char *school;
    char *passions[4];
    bool always_learning;
}   t_prox;

void introduce(t_prox me)
{
    int  i;

    i = 0;
    printf("👋 Hi, I'm %s, a student at %s.\n", me.name, me.school);
    printf("🔍 Passions:\n");
    while (me.passions[i])
    {
        printf("  - %s\n", me.passions[i]);
        i++;
    }
    if (me.always_learning)
        printf("📚 Always curious and learning something new!\n");
}

int main(void)
{
    t_prox me = {
        .name = "prox",
        .school = "42 Luxembourg",
        .passions = {"Linux", "Cybersecurity (OSINT, web, reverse)", "C programming", "Python/Bash scripting", NULL},
        .always_learning = true
    };

    introduce(me);
    printf("\n🎯 My goal: Keep pushing my limits and mastering cybersecurity.\n");

    return 0;
}
```
# printf(tech_stack);
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,cpp,py,bash,arduino,git,github,docker,linux,apple,vim,vscode,notion,postman," />
  </a>
</p>
