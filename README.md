# Custom-Drone
<img width="1089" height="632" alt="model" src="https://github.com/user-attachments/assets/bb9c271a-90ce-41d8-b988-920256057338" />

This is my hack club project to build a medical from scratch with a custom IMU with Arduino &amp; MPU9250. It's my attempt to build a my own custom flight controller as well as PID stabilization as part of this drone project.
<img width="1001" height="719" alt="image" src="https://github.com/user-attachments/assets/24605bc7-c428-4ba1-9c08-294bb76b4471" />

 If looking for my 3D model to review and approve my project, please look in the releases section. Due to the large file size of the .step file when extracted from the original STL file, it had to be uploaded to releases.
 <img width="1270" height="580" alt="image" src="https://github.com/user-attachments/assets/6970f5e0-acf0-4829-80f5-556754bd7835" />


## Bill of Materials (BOM)

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|------|---------|----------|------------------|------|-------------|
| Drone Frame | This will be the frame of the drone that'll hold all the parts and be the structural support. I have decided to use aliminium for the drone, but I'm still at the designing phase for it. | 1 | 25.00 | https://www.amazon.com/gp/product/B0CJ7V24MN/ref=ewc_pr_img_3?smid=A3V9RPWJAAQ27C&th=1 | Amazon |
| CNHL G+Plus 3000mAh 11.1V 3S Lipo Battery | This will be the battery for the drone and it will power it. | 1 | 18.99 | https://chinahobbyline.com/products/cnhl-gplus-series-3000mah-11-1v-3s-70c-lipo-battery-with-xt90-plug?variant=42646820520150&country=US&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&utm_source=google&utm_medium=paid-search&utm_campaign=pmax-all-us&gad_source=1&gad_campaignid=20679418975&gbraid=0AAAAADLM11YyMvG3qD_NDLKjEs94c2Nh8&gclid=CjwKCAjwg_nNBhAGEiwAiYPYA0O9yFw_d91XaKJ55l3Hq386bwSOqDSKlXSrVLVT1E4AFfyVf2CtmxoCuc0QAvD_BwE | China Hobbyline |
| 1400KV Brushless Motors | These will be the motors that generate lift for the drone. | 4 | 33.40 | https://www.robotshop.com/products/e-s-motor-xxd-a2212-brushless-motor-160w-mounting-base-kits-kv-1400?qd=f82c3b340c3f619c5c40ab447d536a69 | Robotshop |
| Raspberry PI 4 4GB | This will be used to connect the usb camera and for video transmission. I already have this, so I will not need to buy it. | 1 | 0.00 | https://www.centralcomputer.com/raspberry-pi-4-model-b-rpi4-modbp-4gb-4gb-ddr4-ram-bcm2711-soc-usb-3-0-poe-enabled.html | Central Computers |
| Arduino UNO R3 | This will be running the flight software and controlling the motors. I already have this, so I will not need to buy it. | 1 | 0.00 | https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/ref=sr_1_1_sspa?crid=6G7O7K7CO1Z8&dib=eyJ2IjoiMSJ9.MazmhFfn-DF8W5oyX_S-tH7qkt_WuogERq_8M3-FTf428RcK1V-0k2CDkJste5CNBGaeyZhzdZU8lFsqqd8UDr_8_HoVEUcLN7hQizeKtT1WlcFNxf38hc9OzCVz-gA1ut4dbKaEA8_EiBspV4fyW5vaaKM5DNYC0RQ4w8r27-zJnMMphk1KJiiCClEj_VHcCIIIGY11AI8nE1SvBySq18V26pH2T89g0DfOs5Pc6Nc.PHAq9TzAk7fqvmCgDpX4rLFbxQsvazigK6K8VrcqWvM&dib_tag=se&keywords=arduino+uno&qid=1773894970&sprefix=arduino+uno%2Caps%2C150&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1 | Amazon |
| GY-91 Board with both MPU-9250 & BMP180 | This will the the 9 Axis Flight Controller for the drone (Gyroscope, Accelerometer, Magnetometer, Altometer) | 1 | 8.79 | https://www.amazon.com/gp/product/B0CMQSYR2Y/ref=ewc_pr_img_1?smid=A2YE8NZRGVUJGM&psc=1 | Amazon |
| 8x4.5 Inch RC Drone Propellers | These will be used on the brushless motors to provide lift for the drone. I am buying 8 pieces instead of 4 in case some breaks during testing. | 1 | 10.79 | https://www.amazon.com/gp/product/B07YYV2JL4/ref=ox_sc_act_title_6?smid=A1THAZDOWP300U&psc=1 | Amazon |
| 3S Li-po Battery Charger | This will be used to charge the battery for the drone. | 1 | 16.99 | https://www.amazon.com/gp/product/B0FPDJP4GK/ref=ox_sc_act_title_4?smid=A3OUEA3BPILM2W&psc=1 | Amazon |
| FLYSKY FS-i6 6Channel 2.4GHz AFHDS2A RC Transmitter & Reciever | This will be used for the radio communication with the drone. | 1 | 49.65 | https://www.amazon.com/gp/product/B07CXL9LCT/ref=ox_sc_act_title_1?smid=A3FG05GA5NMSJ&th=1 | Amazon |
| 30A Brushless Motor ESC | This will be the Electronic Speec Controller for the 4 brushless motors on the drone. Please buy 2 pieces for a total of 4 for each motor. | 2 | 35.18 | https://www.amazon.com/gp/product/B0CZNM4H7H/ref=ox_sc_act_title_6?smid=A3SITFGXOINFFJ&th=1 | Amazon |

**Estimated Total Cost:** Total: $198.79
