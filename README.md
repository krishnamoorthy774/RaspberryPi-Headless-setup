# RaspberryPi Headless Setup
Let's see how to setup raspberry pi zero w without an external monitor.

## Steps
### 1. Install Raspberry Pi Imager "https://www.raspberrypi.com/software/" 
![image](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/9dec8756-1884-4a77-a0ff-5436d5bc1385)

### 3. Download the latest Raspberry Pi OS form the link "https://www.raspberrypi.com/software/operating-systems/"
### 4. Select the downloaded OS navigating to the downloaded path.
![rpi_select_OS](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/406d6132-00af-4bcf-8a7d-6a1ef058a1df)

### 5. Choose Storage.
![rpi_choose_storage](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/a4a4f8db-b3ff-4df3-9c08-fbc0ed3a8890)

### 6.Press write .
![rpi_write_OS](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/a478b800-7d4b-4ccb-9eba-a3e56286b937)


Once it is written and verified it will eject the sd card.


### 7. Remove and reinsert SD card
![rpi_sdcard](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/ec8ac90a-c176-47c8-a4b8-762c595391f6)

### 8. create an empty file and name it "ssh"
![rpi_create_ssh_file](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/fb697926-f757-4e74-8fc0-f72707113a72)

### 9. Create another new text and paste this in the file and rename it to "wpa_conifg"
![rpi_create new fiel](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/dbe735f2-0874-4f35-9553-f5094b0a85db)

![rpi_wifi_credentials](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/e49e328f-8dd7-4aca-9af1-966399835a72)

![rpi_wpa_supplicant-conf](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/4240348e-c470-4b1d-b377-c8546266713b)

### 10.eject the sd card and insert it into raspberrypi.

![rpi_insert_sd-card](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/0ef3875f-1492-453b-9707-908997bc8e14)


### 11.connect the power supply with the pwr pin of the raspberrypi zero w.
![rpi_pwr](https://github.com/krishnamoorthy774/RaspberryPi-Headless-setup/assets/133330566/a46289da-009f-49fe-bd1f-228dfa1b9028)

### 12.wait for few mintues for it to boot.

### you can see the ip address of your raspberry pi in the wifi router.





### Open and edit the file.
Edit the by replacing your ssid and password.


