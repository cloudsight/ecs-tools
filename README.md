# ECS Tools

A finely curated collection of shell tools for common ECS tasks (like shelling into a machine, task, service, etc)

## ecs-host

```
./ecs-host -p [profile] -c [cluster] -s [service name]
```

Example usage:

```
ssh ec2-user@`ecs-host -p profile -c cluster -s myservice`
```

