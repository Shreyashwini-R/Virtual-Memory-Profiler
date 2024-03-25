# Virtual-Memory-Profiler
A Virtual Memory Profiler is a vital tool for analyzing and optimizing the utilization of virtual memory in software. It provides insights into memory usage patterns, potential leaks, and optimization opportunities. ​

Implementation:

memwatch.c:

gcc -o memwatch memwatch.c -lrt

./memwatch

OUTPUT

<img width="406" alt="image" src="https://github.com/Shreyashwini-R/Virtual-Memory-Profiler/assets/140644713/231ac4b9-d8a8-44d9-be91-22502a4bc83f">



pagefault.c:

gcc -o pagefault pagefault.c

./pagefault <pid/command name>

OUTPUT:

<img width="466" alt="image" src="https://github.com/Shreyashwini-R/Virtual-Memory-Profiler/assets/140644713/1a2ed574-60d8-4eec-9723-c2db9a706697">



vp.c:

(To obtain data in csv format for dashboard or graph creation,follow the below steps for execution)
gcc -o vp vp.c


<img width="446" alt="image" src="https://github.com/Shreyashwini-R/Virtual-Memory-Profiler/assets/140644713/075d0937-0510-47c7-af74-ca15a8288e4c">


mem_map.c:

gcc -o mm mem_map.c

./mm

OUTPUT:

<img width="461" alt="image" src="https://github.com/Shreyashwini-R/Virtual-Memory-Profiler/assets/140644713/e2bb3121-2365-421a-8728-cdb7a9716538">




