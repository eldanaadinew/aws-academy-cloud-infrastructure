# Troubleshooting Approach

For each guided environment, troubleshooting followed a consistent order:

1. Confirm the resource exists and is in the expected state.
2. Check VPC, subnet, route-table, and internet-gateway relationships.
3. Review security-group and IAM permissions.
4. Validate instance, storage, database, and load-balancer configuration.
5. Test connectivity and compare the result with the expected architecture.
6. Correct the failed layer, retest, and document the outcome.

Common checks included EC2 status, subnet placement, CIDR ranges, security-group rules, routes, health checks, volume attachment, and service connectivity.
