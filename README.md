# torque-slave

You need to run a pbs master node first.

```sh
docker run -it -P --add-host master:IP_OF_PBS_MASTER cbatchx/torque-slave
```