### Compatibility Matrix

Metrics Server | Metrics API group/version | Supported Kubernetes version
---------------|---------------------------|-----------------------------
0.6.x          | `metrics.k8s.io/v1beta1`  | 1.19+
0.5.x          | `metrics.k8s.io/v1beta1`  | *1.8+
0.4.x          | `metrics.k8s.io/v1beta1`  | *1.8+
0.3.x          | `metrics.k8s.io/v1beta1`  | 1.8-1.21

*Kubernetes versions lower than v1.16 require passing the `--authorization-always-allow-paths=/livez,/readyz` command line flag
