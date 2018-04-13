# 7I76_7I85S_MACH3B1_GPIO pinout

## DB25-P1

[read 7I76 manual](http://www.mesanet.com/pdf/parallel/7i76man.pdf)

|SOC-DB25 PIN | 7I76 P1 PIN | HM2 I/O |  FUNCT   |
|:-----------:|:-----------:|:-------:|:--------:|
| 1           |  1          |  00     | DIR0     |
| 2           |  2          |  02     | DIR1     |
| 3           |  3          |  04     | DIR2     |
| 4           |  4          |  06     | DIR3     |
| 5           |  5          |  08     | DIR4     |
| 6           |  6          |  09     | STEP4    |
| 7           |  SS0TX      |  10     | OUT      |
| 8           |  SS0RX      |  11     | IN       |
| 9           |  SS1TX      |  12     | OUT      |
| 10          |  SS1RX      |  13     | IN       |
| 11          |  11         |  14     | ENCI     |
| 12          |  12         |  15     | ENCB     |
| 13          |  13         |  16     | ENCA     |
| 14          |  14         |  01     | STEP0    |
| 15          |  15         |  03     | STEP1    |
| 16          |  16         |  05     | STEP2    |
| 17          |  17         |  07     | STEP3    |
| 18          |  18         |         | GND      |
| 19          |  19         |         | GND      |
| 20          |  20         |         | GND      |
| 21          |  21         |         | GND      |
| 22          |  22         |         | GND/5V   |
| 23          |  23         |         | GND/5V   |
| 24          |  24         |         | GND/5V   |
| 25          |  25         |         | GND/5V   |

## DB25-P2

[read 7I85S manual](http://www.mesanet.com/pdf/parallel/7i85sman.pdf)

## DB25-P3

mapped to cheap but powerful chinese bob ![mach3b1](mach3b1.jpg)

|SOC-DB25 PIN | MACH3B1 PIN | HM2 I/O |  FUNCT   |
|:-----------:|:-----------:|:-------:|:--------:|
| 1           |  4          |  34     | DIR0/R4  |
| 2           |  6          |  36     | DIR1     |
| 3           |  8          |  38     | DIR2     |
| 4           |  16         |  40     | DIR3     |
| 5           |  14         |  42     | SPL DIR  |
| 6           |  1          |  43     | SPL PWM  |
| 7           |  13         |  44     | INP      |
| 8           |  15         |  45     | INP      |
| 9           |  2          |  46     | OUT/R2   |
| 10          |  3          |  47     | OUT/R3   |
| 11          |  10         |  48     | ENCI     |
| 12          |  11         |  49     | ENCA     |
| 13          |  12         |  50     | ENCB     |
| 14          |  5          |  35     | STEP0    |
| 15          |  7          |  37     | STEP1    |
| 16          |  9          |  39     | STEP2    |
| 17          |  17         |  41     | STEP3    |
| 18          |  --         |         | GND      |
| 19          |  --         |         | GND      |
| 20          |  --         |         | GND      |
| 21          |  --         |         | GND      |
| 22          |  --         |         | GND/5V   |
| 23          |  --         |         | GND/5V   |
| 24          |  --         |         | GND/5V   |
| 25          |  --         |         | GND/5V   |

## DB25-P4

|SOC-DB25 PIN | HM2 I/O |  FUNCT   |
|:-----------:|:-------:|:--------:|
| 1           |  51     | GPIO     |
| 2           |  53     | GPIO     |
| 3           |  55     | GPIO     |
| 4           |  57     | GPIO     |
| 5           |  59     | GPIO     |
| 6           |  60     | GPIO     |
| 7           |  61     | GPIO     |
| 8           |  62     | GPIO     |
| 9           |  63     | GPIO     |
| 10          |  64     | GPIO     |
| 11          |  65     | GPIO     |
| 12          |  66     | GPIO     |
| 13          |  67     | GPIO     |
| 14          |  52     | GPIO     |
| 15          |  54     | GPIO     |
| 16          |  56     | GPIO     |
| 17          |  58     | GPIO     |
| 18          |         | GND      |
| 19          |         | GND      |
| 20          |         | GND      |
| 21          |         | GND      |
| 22          |         | GND/5V   |
| 23          |         | GND/5V   |
| 24          |         | GND/5V   |
| 25          |         | GND/5V   |
