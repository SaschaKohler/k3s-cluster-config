# K3s Cluster Configuration

## Structure
- `apps/`: Application configurations
  - `wordpress-sk/`: sascha-kohler.at WordPress
  - `wordpress-jzl/`: ja-zum-leben.at WordPress
- `cluster/`: Cluster-wide configurations
- `infrastructure/`: Infrastructure components
- `secrets/`: Encrypted secrets (using sealed-secrets)
- `backup/`: Backup configurations and scripts

## Applications
### WordPress Instances
1. sascha-kohler.at (wordpress-sk)
   - Production URL: sascha-kohler.at
   - Namespace: wordpress
   
2. ja-zum-leben.at (wordpress-jzl)
   - Production URL: ja-zum-leben.at
   - Namespace: wordpress-jzl

## Infrastructure
- Ingress: nginx-ingress-controller
- Storage: local-path-provisioner
