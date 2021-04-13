# OpenShift Scheduling Examples

### podAntiAffinity
- [preferredDuringSchedulingIgnoredDuringExecution](pod-anti-affinity/preferred/deployment-hello-pod-anti-affinity-preferred.yaml#L49-L59) - prefer different zones
- [requiredDuringSchedulingIgnoredDuringExecution](pod-anti-affinity/required/deployment-hello-pod-anti-affinity-required.yaml#L52-L60) - require different nodes

### nodeAffinity
- [requiredDuringSchedulingIgnoredDuringExecution](node-affinity/) - require specific zone(s)

