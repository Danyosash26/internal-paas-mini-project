# Requirements – Internal PaaS (Mini Project)

## Functioneel
1. Een developer kan een applicatie deployen in een eigen namespace.
2. Deployments zijn herhaalbaar en versioned (Git).
3. De applicatie is bereikbaar via een vaste ingang (Ingress/LoadBalancer).

## Non-functioneel
4. Role-based access: developer heeft geen cluster-admin rechten.
5. Monitoring: dashboards voor nodes en pods + minimaal 1 alert.
6. Security: minimaal 1 scan (Trivy/kube-bench) + minimaal 1 finding fix.
7. Support Services: processen voor deploy, incident response en recovery zijn ontworpen en getest.

## Acceptatiecriteria (bewijs)
- Screenshots/outputs van kubectl, dashboards en scans in /evidence.
- Scripts in /scripts en manifests in /manifests.
- Procesdocumenten in /docs.
