Linux Kernel Audit Subsystem
=============================================================================
https://git.kernel.org/pub/scm/linux/kernel/git/pcmoore/audit.git  
https://github.com/linux-audit/audit-kernel

The Linux Audit subsystem provides a secure logging framework that is used to
capture and record security relevant events.  It consists of a kernel component
which generates audit records based on system activity, a userspace daemon
which logs these records to a local file or a remote aggregation server, and a
set of userspace tools to for audit log inspection and post-processing.

The main Linux Kernel README can be found at
[Documentation/admin-guide/README.rst](./Documentation/admin-guide/README.rst)

## Online Resources

The canonical audit kernel repository is hosted by kernel.org:

* https://git.kernel.org/pub/scm/linux/kernel/git/pcmoore/audit.git
* git://git.kernel.org/pub/scm/linux/kernel/git/pcmoore/audit.git

There is also an officially maintained GitHub mirror:

* https://github.com/linux-audit/audit-kernel

## Userspace Tools and Test Suites

The audit userspace tools and test suites are hosted by GitHub:

* https://github.com/linux-audit
