# PROCESS

```c
#include <sys/types.h>
#include <unistd.h>

pid_t fork(void);
```



**exec** functions

```c
#include <unistd.h>

int execl(const char* path, const char* arg, ...);
int execlp(const char* file, const char* arg, ...);
int execle(const char* path, const char* arg, ..., char* const envp[]);
int execv(const char* path, char* const argv[]);
int execvp(const char* file, char* const argv[]);
int execve(const char* path, char* const argv[], char* const envp[]);
```

