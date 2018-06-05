# Contract-based Compositional Verification for outsourced Flight Critical Systems

This repository contains links to all the software developed partly (or totally) under the NRA NNX14AI09G. It also contains a subdirectory called [papers](https://github.com/coco-team/coco-project/tree/master/papers) which includes PDF versions of all publications resulting from this project.

## CoCoSim

CoCoSim is an automated analysis and code generation framework for Simulink and Stateflow models. Specifically, CoCoSim can be used to verify automatically user-supplied safety requirements expressed as mode-aware assume-guarantee contracts. Moreover, CoCoSim can be used to generate C and/or Rust code.

* **Project repository**: https://github.com/coco-team/cocoSim2

* **Documentation**: [Installation](https://github.com/coco-team/cocoSim2/blob/master/doc/installation.md), [CoCoSim Features](https://github.com/coco-team/cocoSim2#cocosim-features), [Tutorial Videos](https://github.com/coco-team/cocoSim2#tutorial-videos)

* **CoCoSim models**: [Benchmarks](https://github.com/coco-team/benchmarks), and [Regression Tests](https://github.com/coco-team/regression-test)

## Compiler From CoCoSim IR to Lustre

CoCoSim uses internally a translator from CoCoSim Intermediate Representation of Simulink/StateFlow models to Lustre models. The tool can be used as stand-alone tool, and supports the CoCoSim contract specification blocks.

* **Project repository**: https://github.com/coco-team/ir2lustre

* **Documentation**: [JSON Intermediate Representation of CoCoSim models, and its translation to Lustre](https://github.com/coco-team/ir2lustre/wiki/JSON-Intermediate-Representation-of-CoCoSim-to-Lustre-Programs)

## Kind 2

Kind 2 is multi-engine SMT-based model checker for Lustre programs. It is one of the back-end solvers supported by CoCoSim to verify Lustre models.

* **Project repository**: https://github.com/kind2-mc/kind2

* **Website**: http://kind2-mc.github.io/kind2/

* **Kind 2 web interface**: http://kind.cs.uiowa.edu:8080/app/

* **Documentation**: [User documentation](http://kind.cs.uiowa.edu/kind2_user_doc/), [Developer documentation](http://kind.cs.uiowa.edu/kind2_dev_doc/)

## Teas

Teas is a Test Execution Engine (TEE) compatible with Kind 2's test cases and oracles. It is written in Python, and is able to confront a binary with Kind 2's test cases using an oracle.

* **Project repository**: https://github.com/kind2-mc/testEAS

* **Documentation**: *Test generation* section in [Kind 2 User documentation](http://kind.cs.uiowa.edu/kind2_user_doc/)

## Zustre

Zustre is a modular SMT-based PDR-style verification engine for Lustre programs. It is also an engine to generate mode-aware assume-guarantee style formal contract. It is one of the back-end solvers supported by CoCoSim to verify Lustre models.

* **Project repository**: https://github.com/coco-team/zustre

* **Documentation**: [Compilation](https://github.com/coco-team/zustre/blob/master/README.md#compilation), [Usage](https://github.com/coco-team/zustre/blob/master/README.md#usage), [Demo](https://github.com/coco-team/zustre#demo)

## JDart

JDart is a tool for performing concolic execution on a Java program. It is written as an extension to NASA Java Pathfinder (JPF).

* **Project repository**:  https://github.com/psycopaths/jdart

* **Documentation**: [Installation](https://github.com/psycopaths/jdart#installation), [Usage](https://github.com/psycopaths/jdart#using-jdart)

## SeaHorn

SeaHorn is a fully automated verification framework for LLVM-based languages.

* **Project repository**: https://github.com/seahorn/seahorn

* **Website**: http://seahorn.github.io

* **Documentation**: [Installation](https://github.com/seahorn/seahorn#installation), [Usage](https://github.com/seahorn/seahorn#usage)

## Log2Model

Log2Model is a framework for reasoning on behaviors in log files.

* **Project repository**: https://github.com/coco-team/log2model

* **Documentation**: [Installation](https://github.com/coco-team/log2model#installation), [Usage](https://github.com/coco-team/log2model#examples), [Implementation](https://github.com/coco-team/log2model#implementation)
