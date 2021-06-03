# Example ECS Spot Cluster

This template provides an example ECS Cluster using EC2 spot instances. It creates
an AutoScalingGroup made of multiple spot instances optimized for cost.

The cluster will scale in and out based on ECS target tracking. This cluster isn't
production ready but provides an example of how this type of cluster can be done
via CFN.
