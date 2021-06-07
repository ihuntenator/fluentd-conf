# fluentd.conf files

Fluentd configuration files for simple testing etc.

| fluentd.conf | fluentd.conf.in_forward.stdout |
| fluentd.conf.debug.in_forward.stdout | debug on in_forward to stdout |
| fluentd.conf.in_file.hec | in_file from container logs to HEC |
| fluentd.conf.in_forward.stdout | in_forward to stdout |

Use curl to grab raw:
```
curl https://raw.githubusercontent.com/ihuntenator/fluentd.conf/master/fluentd.conf -o docker/fluentd.conf
```

