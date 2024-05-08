# Multi-Threading

Multithreading refers to the capability of a Central Processing Unit (CPU) to partition a singular process into numerous threads of execution, enabling them to operate simultaneously. Each execution thread represents the smallest set of programmed instructions, managed independently by a scheduler. This scheduler, responsible for deciding when, where, and in what sequence threads execute, operates as an abstraction layer.

![image](https://github.com/OjaswaniB/multithreading/assets/118871180/3ed0046f-6c0f-45ce-a97c-b3ff1a27bb78)

The provided Python script assesses the duration required for matrix multiplication across varying thread counts. By implementing multi-threading, it parallelizes the matrix multiplication process and generates a graph illustrating the correlation between thread count and average duration.

Typically, the graph showcases a decline in duration as thread count increases, reaching an optimal point, typically around the number of physical CPU cores (e.g., 4 in this case). Beyond this threshold, adding more threads can result in increased duration due to additional thread management overhead, contention for shared resources like cache, and potential saturation of available CPU resources. This phenomenon, known as "over-subscription," can lead to diminishing returns or even performance degradation.
