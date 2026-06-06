```c
static const char* HELLO = "EVERYONE";

typedef struct {
  uint8_t age;
  char *interests;
  char *working_as;
  char *university;
  char *faculty;
} profile_t;

profile_t mateusz = {
  .age = 23;
  .interests = "power electronics, microwaves, physics";
  .working_as = "electrical engineer @ Woodward";
  .university = "AGH University of Science and Technology";
  .faculty = "Electronics and Telecomunications";
}
```
