Ymodem for melis

```
└── source
    └── ekernel
        ├── components
        │   ├── Makefile
        │   ├── aw
        │   │   └── newlib
        │   │       └── syscalls.c
        │   └── thirdparty
        │       ├── Kconfig
        │       ├── Makefile
        │       └── ymodem
        │           ├── Makefile
        │           ├── cmd_ry_sy.c
        │           ├── ymodem.c
        │           └── ymodem.h
        └── drivers
            ├── drv
            │   └── source
            │       └── serial
            │           └── uart_drv.c
            ├── include
            │   └── hal
            │       └── hal_uart.h
            └── rtos-hal
                ├── hal
                │   └── source
                │       └── uart
                │           └── hal_uart.c
                └── include
                    └── hal
                        └── hal_uart.h
```