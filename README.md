This is a sample project, feel free to clone it and do what you want
with it.

The "Examples" subsection below shows examples of approval checks based
on the OWNERS structure of this repo.

The "Owners" subsection below shows the list of _all_ usernames aggregated
from all OWNERS files.

The "Directories" subsection below shows the directory tree. Useful for a quick
inspection of this repo.


## Examples

is-approved --approvers buzza,dwightf Workspace/Apollo/Source/Eleven/main.c
    Returns YES
is_approved --approvers dwightf,robertc Workspace/Apollo/Source/Eleven/main.c
    Returns YES
is-approved --approvers dwightf,alberte Workspace/Apollo/Source/Eleven/main.c
    Returns NO
is-approved --approvers admin Workspace/ThirdParty/CocoaLumberjack/main.c
    Returns YES


## Owners

admin
alberte
annec
buzza
daniellak
dwightf
richardf
robertc
stevej


## Directories

.
├── Configs
│  ├── config.rc
│  └── OWNERS
├── OWNERS
├── README
├── Tools
│  ├── builder
│  └── OWNERS
└── Workspace
   ├── Apollo
   │  ├── OWNERS
   │  ├── Source
   │  │  ├── Eleven
   │  │  │  ├── main.c
   │  │  │  └── OWNERS
   │  │  └── Thirteen
   │  │     └── main.c
   │  └── Tests
   │     └── test.c
   ├── BlueBook
   │  ├── Source
   │  │  └── main.c
   │  └── Tests
   │     └── test.c
   ├── Durango
   │  ├── OWNERS
   │  ├── Source
   │  │  └── main.c
   │  └── Tests
   │     └── test.c
   ├── Hanks
   │  ├── Source
   │  │  └── main.c
   │  └── Tests
   │     └── test.c
   ├── Kodiak
   │  ├── OWNERS
   │  ├── Source
   │  │  └── main.c
   │  └── Tests
   │     └── test.c
   ├── Manhattan
   │  ├── OWNERS
   │  ├── Source
   │  │  └── main.c
   │  └── Tests
   │     └── test.c
   ├── ThirdParty
   │  ├── AFNetworking
   │  │  └── main.c
   │  ├── CocoaLumberjack
   │  │  └── main.c
   │  └── OWNERS
   └── Titan
      ├── OWNERS
      ├── Source
      │  └── main.c
      └── Tests
         └── test.c
