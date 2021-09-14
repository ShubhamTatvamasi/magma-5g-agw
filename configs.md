# configs

add following line in `mme.yml`
```
congestion_control_enabled: true
enable_converged_core: true
```

add following lines in `pipelined.yml`
```
ovs_internal_sampling_port_number: 15578
ovs_internal_sampling_fwd_tbl_number: 201

# For 5G Functionality Support flag
5G_feature_set:
 enable: True
 node_identifier: 192.168.200.1

paging_timeout: 30
classifier_controller_id: 5
```

add following line in `sessiond.yml`
```
converged_access: true
```

add following line in `subscriberdb.yml`
```
m5g_auth_proc: True
```

add following line in `gateway.mconfig`
```
"enableConvergedCore": true
```

check ports:
```bash
sudo netstat -l | grep sctp
```



