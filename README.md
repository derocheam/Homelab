# Homelab

### Tech stack

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://simpleicons.org/icons/ansible.svg"></td>
        <td><a href="https://www.ansible.com">Ansible</a></td>
        <td>Automate bare metal provisioning and configuration</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/argo/icon/color/argo-icon-color.svg"></td>
        <td><a href="https://argoproj.github.io/cd">ArgoCD</a></td>
        <td>GitOps tool built to deploy applications to Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/jetstack/cert-manager/raw/master/logo/logo.png"></td>
        <td><a href="https://cert-manager.io">cert-manager</a></td>
        <td>Cloud native certificate management</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/314135?s=200&v=4"></td>
        <td><a href="https://www.cloudflare.com">Cloudflare</a></td>
        <td>DNS and Tunnel</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
        <td><a href="https://www.docker.com">Docker</a></td>
        <td>Ephemeral PXE server and convenient tools container</td>
    </tr>
    <tr>
        <td><img width="32" src="https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png"></td>
        <td><a href="https://ubuntu.com/download/server">Ubuntu Server</a></td>
        <td>Base OS for Kubernetes nodes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Gitea_Logo.svg"></td>
        <td><a href="https://gitea.com">Gitea</a></td>
        <td>Self-hosted Git service</td>
    </tr>
    <tr>
        <td><img width="32" src="https://grafana.com/static/img/menu/grafana2.svg"></td>
        <td><a href="https://grafana.com">Grafana</a></td>
        <td>Operational dashboards</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/helm/icon/color/helm-icon-color.svg"></td>
        <td><a href="https://helm.sh">Helm</a></td>
        <td>The package manager for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/k3s/icon/color/k3s-icon-color.svg"></td>
        <td><a href="https://k3s.io">K3s</a></td>
        <td>Lightweight distribution of Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/kubernetes/icon/color/kubernetes-icon-color.svg"></td>
        <td><a href="https://kubernetes.io">Kubernetes</a></td>
        <td>Container-orchestration system, the backbone of this project</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/grafana/loki/blob/main/docs/sources/logo.png?raw=true"></td>
        <td><a href="https://grafana.com/oss/loki">Loki</a></td>
        <td>Log aggregation system</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/longhorn/icon/color/longhorn-icon-color.svg"></td>
        <td><a href="https://longhorn.io">Longhorn</a></td>
        <td>Cloud native distributed block storage for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/60239468?s=200&v=4"></td>
        <td><a href="https://metallb.org">MetalLB</a></td>
        <td>Bare metal load-balancer for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/1412239?s=200&v=4"></td>
        <td><a href="https://www.nginx.com">NGINX</a></td>
        <td>Kubernetes Ingress Controller</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/prometheus/icon/color/prometheus-icon-color.svg"></td>
        <td><a href="https://prometheus.io">Prometheus</a></td>
        <td>Systems monitoring and alerting toolkit</td>
    </tr>
    <tr>
        <td><img width="32" src="https://docs.renovatebot.com/assets/images/logo.png"></td>
        <td><a href="https://www.whitesourcesoftware.com/free-developer-tools/renovate">Renovate</a></td>
        <td>Automatically update dependencies</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/47602533?s=200&v=4"></td>
        <td><a href="https://tekton.dev">Tekton</a></td>
        <td>Cloud native solution for building CI/CD systems</td>
    </tr>
    <tr>
        <td><img width="32" src="https://trow.io/trow.png"></td>
        <td><a href="https://trow.io">Trow</a></td>
        <td>Private container registry</td>
    </tr>
    <tr>
        <td><img width="32" src="https://simpleicons.org/icons/vault.svg"></td>
        <td><a href="https://www.vaultproject.io">Vault</a></td>
        <td>Secrets and encryption management system</td>
    </tr>
    <tr>
        <td><img width="32" src="https://docs.zerotier.com/img/ZeroTierIcon.png"></td>
        <td><a href="https://zerotier.com">ZeroTier</a></td>
        <td>VPN without port forwarding</td>
    </tr>
</table>
### Hardware

- SuperMicro CSE-826(https://supermicroesx.derochea.com):
    - MB: `X9DRI-F`
    - CPU: `XEON E5-2680V2 10 CORE 2.80GHz`
    - RAM: `128GB Samsung M386B4G70DM0-CMA4+32GB+4Rx4+PC3-14900L+DDR3-1866MHz+Load+Reduced+DIMM`
    - ESX SSDs: 
      - `250GB Samsung_SSD_840_EVO_250GB`
      - `256GB C4002DMTFDDAK256MAM`
    
    !!Passthrough to unraid via LSI SAS2008 onboard SATA and NVME PCI adapter
    - Array: `16TB Usable + 10GB Parity`
      - `8TB WDC_WD80EZAZ-11TDBA0_1SG9K1LZ - Disk 2`
      - `8TB WDC_WD80EMAZ-00WJTA0_7P0J3ZDC - Disk 4`
      - `10TB WDC_WD100EMAZ-00WJTA0_JEK2JDKZ - Parity`
    - Unassigned Disks: `110TB`
      - `18TB WDC_WD180EDGZ-11B2DA0_3FH5DPDT - Dev 1`
      - `18TB WDC_WD180EDGZ-11B2DA0_3FG5KJGT (sdk) - Dev2`
      - `14TB WDC_WD140EDGZ-11B2DA2_2BGDSD7N (sdh) - Dev3`
      - `14TB WDC_WD140EDGZ-11B1PA0_Y6G7PW4C (sdg) - Dev4`
      - `12TB ST12000NE0008-2JL101_ZL00BDFT (sde) - Dev5`
      - `14TB WDC_WD140EDGZ-11B1PA0_9LGZLXTG (sdf) - Dev6`
      - `2TB WDC_WD20EARX-00PASB0_WD-WCAZAH621663 (sdl) - Dev7`
      - `18TB WDC_WD180EDGZ-11B2DA0_3GGD0SBF (sdi) - Dev8`
    - NVME: `1TB Samsung_SSD_970_EVO_1TB`
    - Unraid Docker:
      - `unifi-controller`
      - `code-server`
      - `mariadb`
      - `gitea`
      - `nginx-proxy-manager`
      - `machinaris`
      - `ddclient`
      - `changedetection.io`
      - `Tailscale`
      - `vaultwarden`
      - `borgmatic`
      - `glances`
      - `Docker-WebUI`

- HP290 (Ubuntu 20.04.5 LTS)
    - CPU: `Intel(R) Celeron(R) G4900 CPU @ 3.10GHz`
    - RAM: `12GB`
    - SSD: `256GB Samsung SSD 840`
    - Docker:
      - `home-assistant`
      - `eclipse-mosquitto`
      - `zwavejs2mqtt`
      - `borgmatic`
      - `cloudflared`
      - `node-red`
      - `plex`
      
 - HP290 (OPNsense 22.7.10_2)
    - CPU: `Intel(R) Celeron(R) G4900 CPU @ 3.10GHz`
    - RAM: `12GB`
    - SSD: `16GB Intel+Optane+Memory+M10+16GB+(MEMPEK1J016GAD)`
    
 - HP EliteDesk 800 G5 SFF
    - CPU: `i5-9600 3.1GHz`
    - RAM: `48GB A-Tech 32GB DDR4 2666 MHz UDIMM PC4-21300 (PC4-2666V) CL19 DIMM 2Rx8 Non-ECC Desktop RAM Memory Module`
    - SSD:
      - `256GB`
      - `500GB Samsung_SSD_840_EVO`
 ### Networking
 - OPNsense 22.7.10_2 Router/Firewall
    - DHCP
        - Provides hostnames to unbound
    - Unbound DNS
        - Host overrides to forward custom DNS names to NginxProxyManager
    - Adguard
 - NginxProxyManager(on Unraid)
    - provides wildcard letsencrypt cert for domain(namecheap) via Cloudflare
    - provides https custom domain names for internal services with ssl certificates
 - USW-Lite-8-PoE
 - USW-Flex-Mini
 - UAP-FlexHD
 - UAP-AC-Lite
    
      
    
