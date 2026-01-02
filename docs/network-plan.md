# Network Plan – Internal PaaS

## Subnet
- Node subnet: 10.60.10.0/24
- Gateway: 10.60.10.1 (if applicable)

## Nodes (static IP)
- k3s-master: 10.60.10.10
- k3s-worker1: 10.60.10.11
- k3s-worker2: 10.60.10.12

## LoadBalancer IPs (MetalLB pool)
- 10.60.10.50 - 10.60.10.60

## Rationale
- /24 subnet = simple, readable, and avoids overlap
- Static IPs = easier support, monitoring, and incident response
- MetalLB provides external IPs for services in a local lab
