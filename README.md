# `> BOOTING PROFILE...`

```asm
; ============================================================
;                  SYSTEM INITIALIZATION
; ============================================================

MOV     AX, 0001h
MOV     BX, 0000h

PRINT   "HEY THERE, I AM"

; ------------------------------------------------------------
;                     USER IDENTIFICATION
; ------------------------------------------------------------

MOV     USER, "aliraza"

PRINT   "aliraza"

; ------------------------------------------------------------
;                     SYSTEM STATUS
; ------------------------------------------------------------

STATUS  = ONLINE
MODE    = DEVELOPER
MIND    = CURIOUS
BUILD   = IN_PROGRESS

; ============================================================
;                 WELCOME TO MY PROFILE
; ============================================================
```

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   H E Y   T H E R E ,   I   A M                             │
│                                                              │
│        █████╗ ██╗     ██╗██████╗  █████╗ ███████╗ █████╗    │
│       ██╔══██╗██║     ██║██╔══██╗██╔══██╗╚══███╔╝██╔══██╗   │
│       ███████║██║     ██║██████╔╝███████║  ███╔╝ ███████║   │
│       ██╔══██║██║     ██║██╔══██╗██╔══██║ ███╔╝  ██╔══██║   │
│       ██║  ██║███████╗██║██║  ██║██║  ██║███████╗██║  ██║   │
│       ╚═╝  ╚═╝╚══════╝╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝   │
│                                                              │
│                       [ ALIRAZA ]                            │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

## `> WHOAMI`

```asm
NAME        DB "Ali Raza"
USERNAME    DB "aliraza"

ROLE        DB "Developer"
INTERESTS   DB "Code, Systems, Technology"
CURRENTLY   DB "Building & Learning"

RETURN      0
```

## `> ABOUT_ME`

```text
Hello, world.

I'm Ali Raza — a developer who enjoys turning ideas
into things that actually work.

I like exploring technology, building projects,
breaking things, fixing them, and learning something
new along the way.

$ ./aliraza --status

[+] System      : ONLINE
[+] Creativity  : ACTIVE
[+] Curiosity   : HIGH
[+] Coffee      : REQUIRED
[+] Bugs        : EXPECTED
[+] Learning    : CONTINUOUS
```

## `> SKILLS`

```asm
; LOADED MODULES

[████████████████████] CODE
[██████████████████░░] PROBLEM_SOLVING
[█████████████████░░░] SYSTEMS
[████████████████░░░░] LEARNING
[███████████████░░░░░] DEBUGGING
```

## `> CONNECT`

```text
┌─────────────────────────────────────────┐
│                                         │
│   GitHub   : github.com/aliraza         │
│   Status   : ONLINE                     │
│                                         │
│   > Feel free to explore my projects.   │
│   > Fork something.                     │
│   > Open an issue.                      │
│   > Say hello.                          │
│                                         │
└─────────────────────────────────────────┘
```

```asm
; ============================================================
;                    END OF TRANSMISSION
; ============================================================

INT     21h
RET

; "KEEP BUILDING."
```
