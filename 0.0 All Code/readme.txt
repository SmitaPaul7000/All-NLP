
ref:
https://blog.floydhub.com/multiprocessing-vs-threading-in-python-what-every-data-scientist-needs-to-know/
Multiaprocessing:
Multiprocessing is ability of a system to support more than one processor at the same time. Applications in a multiprocessing system are broken to smaller routines that run independently. The operating system allocates these threads to the processors improving performance of the system.

Why multiprocessing?

Consider a computer system with a single processor. If it is assigned several processes at the same time, it will have to interrupt each task and switch briefly to another, to keep all of the processes going.
This situation is just like a chef working in a kitchen alone. He has to do several tasks like baking, stirring, kneading dough, etc.

A multiprocessing system can have:
1. multiprocessor, i.e. a computer with more than one central processor.
2. multi-core processor, i.e. a single computing component with two or more independent actual processing units (called “cores”).

The CPU can easily executes several tasks at once, with each task using its own processor.
It is just like the chef in last situation being assisted by his assistants. Now, they can divide the tasks among themselves and chef doesn’t need to switch between his tasks. 


Each process has its own memory space it uses to store the instructions being run, as well as any data it needs to store and access to execute.
