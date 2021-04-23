## Pod Topology Spread Contraints

**Example 1: `topologyKey = zone` and `whenUnsatisfiable = ScheduleAnyway`**

View the example manifests
```
oc kustomize topology-spread-contraints/schedule-anyway/
```

Apply it in your cluster
```
oc apply -k topology-spread-contraints/schedule-anyway/
```

**Example 2: `topologyKey = zone` and `whenUnsatisfiable = DoNotSchedule`**

View the example manifests
```
oc kustomize topology-spread-contraints/do-not-schedule/
```

Apply in your cluster
```
oc apply -k topology-spread-contraints/do-not-schedule/
```
