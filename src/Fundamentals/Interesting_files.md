# Interesting Files
- kubelet.conf (bootstrap-kubelet.conf during TLS bootstrap)
- controller-manager.conf
- scheduler.conf
- admin.conf for the cluster admin and kubeadm itself
- super-admin.conf for the cluster super-admin that can bypass RBAC
- **ca.crt**: The Kubernetes root-CA certificate
- **ca.key**: The Kubernetes root-CA private key
- **sa.pub**: The public key used by the controller manager when singing a Service Account
- **sa.key** The private key used by the controller manger when sigining a Service account
- **config.json**: The docker config file. Typically stored at `/home/user/.docker/config.json` Can contain credentials for pushing/pulling images to registries if configured with `docker login`