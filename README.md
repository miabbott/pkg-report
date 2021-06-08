# pkg-report
A utility to report how the version of a package changed during an RHCOS release

Usage:

```
$ ./pkg_report.py --release rhcos-4.7 --package podman
47.82.202010110827-0 = podman-1.9.3-3.rhaos4.6.el8.x86_64 on 2020-10-11 08:27:00
47.82.202011061042-0 = podman-1.9.3-4.rhaos4.7.el8.x86_64 on 2020-11-06 10:42:00
47.83.202011240323-0 = podman-2.0.5-5.module+el8.3.0+8221+97165c3f.x86_64 on 2020-11-24 03:23:00
47.83.202103010456-0 = podman-2.2.1-7.module+el8.3.1+9857+68fb1526.x86_64 on 2021-03-01 04:56:00
```
