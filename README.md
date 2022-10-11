# Pi-Cluster
Utilising 80+ Raspberry Pi 2s for a scalable simulation and compute cluster with Linux for Ros Work.

## Initial thoughts
- Utilize Docker / Kubernetes, great for learning and experimenting.
- Automated redeployment
- Multi-user access (sol: through Rancher's users)
- Raspberry Pi 2, limited in Ethernet bandwidth, vast number of nodes.
  - external router and switches?
  - Network boot to NFS storage cluster (Raspberry Pi 4 maybe too weak for 50+?)
  
## Plan
- [ ] Acquire own Pi4 and Pi2, router and SSD.
- [ ] Set up fresh install of Raspbian / other OS
- [ ] Set up master node with network boot server stuff
- [ ] tbd...
- [ ] deadline? pffth

## Resources
Some interesting articles to setup the cluster.
- https://www.raspberrypi.com/tutorials/cluster-raspberry-pi-tutorial/
- https://blog.zachinachshon.com/k3s-installation/
- https://sahansera.dev/building-your-own-private-kubernetes-cluster-on-a-raspberry-pi-4-with-k3s/
- https://medium.com/swlh/yet-another-raspberry-pi-k8s-cluster-part-2-k3s-installation-fc93fb5313a1
