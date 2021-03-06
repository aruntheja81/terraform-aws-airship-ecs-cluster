# Mixed cluster

Creates a fixed size ECS cluster backed by a mixture of different instance types, both spot- and on demand instances.

The magic happens in the "enable_mixed_cluster", "mixed_cluster_instances_distribution", and "mixed_cluster_launch_template_override" parameters.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| public\_key | The public key for the SSH key needed to SSH to the EC2 instances in the ECS cluster | string | `"ssh-rsa AAAAB3NzaC1yc2EAAAABJQAAACEApggnkvLGHyI5/k8auZl4BuIgWFXmVanCUu9hD0wr35c= dummy-key"` | no |
| region | The AWS region to deploy in | string | `"eu-west-1"` | no |

