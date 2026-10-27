## Stateless Firewalls
- firewall monitor traffic and only allow traffic permitted by a set of predefined rules
- inbound and outbound rules

## Stateful Firewalls
- stateful firewalls are intelligent enough to understand which request and response are part of the same connection
- automatically permits a response if the request is permitted
- don't need the outbound rule

## Network Access Control List (NACL)
- NACLs filter traffic entering and leaving a subnet

## Security Groups
- acts as firewalls for individual resources (EC2, LB, RDS)
- are stateful
