# Homelab
Details about my HomeLab

### Hardware

- SuperMicro CSE-826(https://supermicroesx.derochea.com):
    - MB: `X9DRI-F`
    - CPU: `XEON E5-2680V2 10 CORE 2.80GHz`
    - RAM: `128GB Samsung M386B4G70DM0-CMA4+32GB+4Rx4+PC3-14900L+DDR3-1866MHz+Load+Reduced+DIMM`
    - ESX SSDs: 
      - `250GB Samsung_SSD_840_EVO_250GB`
      - `256GB C4002DMTFDDAK256MAM`
    ### Passthrough to unraid via LSI SAS2008 onboard SATA and NVME PCI adapter
    - Array: `16TB Usable + 10GB Parity`
      - 8TB WDC_WD80EZAZ-11TDBA0_1SG9K1LZ - Disk 2
      - 8TB WDC_WD80EMAZ-00WJTA0_7P0J3ZDC - Disk 4
      - 10TB WDC_WD100EMAZ-00WJTA0_JEK2JDKZ - Parity
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
    - Docker:
      - unifi-controller
      - code-server
      - mariadb
      - gitea
      - nginx-proxy-manager
      - machinaris
      - ddclient
      - changedetection.io
      - Tailscale
      - vaultwarden
      - borgmatic
      - glances
      - Docker-WebUI

- HP290 (Ubuntu 20.04.5 LTS)
    - CPU: `Intel(R) Celeron(R) G4900 CPU @ 3.10GHz`
    - RAM: `12GB`
    - SSD: `256GB Samsung SSD 840`
    - Docker:
      - home-assistant
      - eclipse-mosquitto
      - zwavejs2mqtt
      - b3vis/borgmatic
      - cloudflared
      - node-red
      - plex
      
 - HP290 (OPNsense 22.7.10_2)
    - CPU: `Intel(R) Celeron(R) G4900 CPU @ 3.10GHz`
    - RAM: `12GB`
    - SSD: `16GB Intel+Optane+Memory+M10+16GB+(MEMPEK1J016GAD)`
    
 - HP EliteDesk 800 G5 SFF
    - CPU: i5-9600 3.1GHz
    - RAM: 48GB `A-Tech 32GB DDR4 2666 MHz UDIMM PC4-21300 (PC4-2666V) CL19 DIMM 2Rx8 Non-ECC Desktop RAM Memory Module`
    - SSD:
      - 256GB
      - 500GB Samsung_SSD_840_EVO
    
      
    
