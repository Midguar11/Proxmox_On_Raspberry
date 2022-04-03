
# iNFO

- Make Home Lab on Raspberry Pi with Proxmox

# Hardware:

- Raspberry Pi 4 / 4GB
- 1 TB HDD
- Internet connection via ethernet


# Downloads

- raspberry installer: https://www.raspberrypi.com/software/

# Install basic OS

- plug in SD Card card on the card reader
- use Raspberry PI Manager, choose os: other / Lite 64 bit Debian Bullseye
- when completed install, plug back The Sd Card in Rasp

# Interactive Automatic Installer ( github Pimox)

- first boot change pass, Base user: pi Base pass: raspberry
- change it any new : sudo passwd
- sudo -s
   
      curl https://raw.githubusercontent.com/pimox/pimox7/master/RPiOS64-IA-Install.sh > RPiOS64-IA-Install.sh
      chmod +x RPiOS64-IA-Install.sh

- Follow the prompts

      ./RPiOS64-IA-Install.sh

 - when finish log ing Base user: root, pass: you gave
    
       apt upgrade -y
       reboot    

- Chek screen https://xxx.xxx.0.xxx:8006
- open ip in the bwoser, give security exception



