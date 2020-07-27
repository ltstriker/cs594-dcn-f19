# cs594-dcn-hw2
Starter code for HW2 in CS594: DCN

**NOTE: You can use the command `grip . <ip> &` where `<ip>` is the IP
of your CloudLab server to view the README.md files from your web
browser.**

## Part 0: Setup the cluster
Follow the steps in `env` (See the [README](env/README.md))

## Part 1: Experiment with existing RDMA benchmark programs
Follow the steps in `exps/rdma_seg/` (See the
[README](exps/rdma_seg/README.md)) and complete the appropriate section
of your writeup in `writeup/WRITEUP.md`.

## Part 2: Write your own RDMA application 
In the `code` directory, create your own application that uses RDMA.
You will use this application in Part 3.

Your are encouraged to use any on-line guides and repos to develop this
application.  The following is an okay play to start:
- [Mellanox OFED source](http://www.mellanox.com/page/products_dyn?product_family=26&mtag=linux_sw_drivers)
    - Example code demonstrating the latest software/hardware features
      can be found within libibverbs*/examples and perftest*
- [https://github.com/jcxue/RDMA-Tutorial/wiki](https://github.com/jcxue/RDMA-Tutorial/wiki)
- [https://github.com/linzion/RDMA-example-application](https://github.com/linzion/RDMA-example-application)
- [RDMAMojo](http://www.rdmamojo.com/)

## Part 3: Benchmark your own RDMA application
In the `exps/hw2` directory, create an experiment that benchmarks the
performance of your RDMA program.
- Your writeup should be located in `writeup/WRITEUP.md`.
- You should choose a dimension of RDMA performance to evaluate.  See
  the assignment for some suggested performance dimensions to benchmark.
- You are encouraged but not required to use some of the existing
  experimental infrastructure.
