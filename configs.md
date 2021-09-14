# configs

add following line in `mme.yml`
```
congestion_control_enabled: true
```

add following line in `pipelined.yml`
```
ovs_internal_sampling_port_number: 15578
ovs_internal_sampling_fwd_tbl_number: 201

# For 5G Functionality Support flag
5G_feature_set:
 enable: True
 node_identifier: 192.168.200.1
```

