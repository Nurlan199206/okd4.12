# OKD 4.12 Home lab

```OKD version: 4.12.0-0.okd-2023-01-21-055900```


```openshift-install create manifests```

```openshift-install create ignition-configs```

```openshift-install --dir=. wait-for bootstrap-complete --log-level=debug```

```nmcli con mod "Wired connection 1" ipv4.addresses 10.160.1.x/24```

```nmcli con mod "Wired connection 1" ipv4.gateway 10.160.1.1```

```nmcli con mod "Wired connection 1" ipv4.dns "10.201.1.12,10.201.1.13"```

```nmcli con mod "Wired connection 1" ipv4.method manual - change from DHCP to static```

```nmcli conn show```


| Type          | Resources     |
| ------------- |:-------------:|
| master,worker | 8vCPU,8GB RAM, 40 DISK |
| master,worker | 8vCPU,8GB RAM, 40 DISK |
| master,worker | 8vCPU,8GB RAM, 40 DISK |



![alt text](https://github.com/Nurlan199206/okd4.12/blob/main/okd-1.png "OKD 4.12")


![alt text](https://github.com/Nurlan199206/okd4.12/blob/main/okd-2.png "")

![alt text](https://github.com/Nurlan199206/okd4.12/blob/main/task%20mgr.png "Logo Title Text 1")






