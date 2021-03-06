[BMC (Bare-Metal Container)](http://www.itri.aist.go.jp/cpc/research/bmc/) offers an environment to run a container (Docker) image with a suitable Linux kernel on a remote physical machine.
BMC allows to change the kernel and its settings for the container (Docker) image.
As a result, the application extracts the full performance of the physical machine.

The following figure shows the difference in application invocation between traditional style and BMC.
The traditional style is a system-centric architecture as it assumes the system software is fixed, running all the time, and unalterable by users.
In contrast, BMC allows users to change the kernel and the machine for each application, which we describe as an application-centric architecture.

![BMC arch](http://www.itri.aist.go.jp/cpc/research/img/research-4-001.png)

A pre-built BMC image using DIND (Docker in Docker) technique is offered.
Users can avoid burdensome setting up (ex. Apache CGI, etc).
We recommend new users to try this pre-built version.

https://hub.docker.com/r/baremetalcontainer/bmc/

# Paper & Presentation
* [1] K.Suzaki, H.Koie, and R.Takano, "Bare-Metal Container  --- Direct Execution of a Container Image on a Remote Machine with an Optimized Kernel ---", [the 18th IEEE High Performance Computing and Communications (HPCC)](http://www.swinflow.org/confs/2016/hpcc) Dec.2016. / [Ppaer PDF](https://www.researchgate.net/profile/Kuniyasu_Suzaki/publication/311716297_Bare-Metal_Container_---_Direct_execution_of_a_container_image_on_a_remote_machine_with_an_optimized_kernel_---/links/58579ed508ae77ec370a824a.pdf?origin=publication_detail&ev=pub_int_prw_xdl&msrp=SO2YfYKNZvcGeCUGx4SaB-86NvgO39wgRTrI-XPjzcVhMlrU4DVMuUPdgjvIKkvTaHcru-NEuA1hx78YoXbF8XfP5EUc0_hbZv1wdjPkNuI.YewcWchFqz5N0SCFw41VDGE98RHGohomAv-mYnCSaO4rMGq7KDbW74DHw3KWTj9az4S4RKatGQNuTfRncuyyDw.9tAC6ocUUgqQxKOXvipyty6Y0miNCbYDqoS2tsPJ8mP88-_lwDIE64Xu2epD1YQd0dqnyMDUNR3l_-v19VYvOQ) / [Slide PDF](http://www.slideshare.net/suzaki/baremetal-container-presented-at-hpcc2016)
* [2] K.Suzaki, "Bare-Metal Container", [Open Source Summit Japan 2017](http://events.linuxfoundation.jp/events/open-source-summit-japan/program/schedule), July.2017.
* [3] K.Suzaki, H.Koie, and R.Takano, "Profile Guided Kernel Optimization for Individual Container Execution on Bare-Metal Container" [SC17 poster](http://sc17.supercomputing.org/presentation/?id=post164&sess=sess293)

# Exhibition
* [1] SuperComuting16 (SC16) [AIST booth 1709] Nov.2016 http://sc16.supercomputing.org/
* [2] SuperComuting17 (SC17) [AIST booth 1211] Nov.2016 http://sc17.supercomputing.org/

