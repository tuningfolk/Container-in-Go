# Container-in-Go
building a container

## The system behind containers
namespaces, cgroups, and layered filesystems

Clone namespaces in Go:
using flags: syscall.CLONE_NEWUTS, syscall.CLONE_NEWPID, syscall.CLONE_NEWNS
