# Benchmark data

This folder contains the raw benchmark results computed and used by
[zkalc](https://github.com/mmaker/zkalc) and [zk-Harness](https://github.com/zkCollective/zk-Harness).

## Structure

```
<circuits or math>/<machine>/<framework>/
```

In the `math` directory, we save the raw results for low-level arithmetic (e.g., field operations and curve operations),
whereas the `circuits` directory contains the results for the circuits (e.g., exponentiate circuit)

* `libraries.json`: This file lists the versions of libraries used in the math experiments, the supported curves, and the ZK-SNARK frameworks that are using them.
* `curves.json`: Here, you can find the details of various curves utilized in the math experiments.
* `machines.json`: Describes the specifications of the machines used to run the experiments.
