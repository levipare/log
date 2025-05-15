# Log
Logging library for C

![preview image](https://github.com/user-attachments/assets/9e9b08ce-fd60-4604-a473-0c292864d232)

## Example Usage
Use one of the following macros like you would use printf.
```c
log_debug(const char *fmt, ...);
log_info(const char *fmt, ...);
log_warn(const char *fmt, ...);
log_error(const char *fmt, ...); 
log_fatal(const char *fmt, ...);
```

```c
#include "log.h"

int main() {
    int x = 10;
    log_debug("x = %d", x);

    log_error("An error has occured");
}
```
