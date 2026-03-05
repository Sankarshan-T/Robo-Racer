# Robo-Racer
Building a RC racing robot capable of navigating sand pits, ramps and a lot more fun stuff.
This project was made because I was always fond of rc cars and I wanted to try something new.


https://github.com/user-attachments/assets/db7c474e-a4ad-4f39-b993-d5889bbc2405

### NO CODE NEEDED FOR THIS ROBOT


## Electronics Required
1. Electrocraze 20D dual channel ESC (1 (Controls the bot without code)
2. Flysky FSi6X Transmitter and receiver (1) (A remote control for the bot)
3. Johnson DC motors 1000 RPM 12V (4) (motors for the bot  to  move)
4. Lipo Battery 3S 2200mAh  (A battery to power the motors)
5. XT-60 connector for battery (A connector for the battery)
<img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/18b38ca5-3afb-47c9-80d9-05916bc7e849" />

## Chassis Design
The chassis design for the model can be found in the CAD folder along with sliced files for 3D printing.
<img width="646" height="411" alt="image" src="https://github.com/user-attachments/assets/6a7fe7be-9a88-4e53-b6fb-91da495c0db2" />

## Assembly Instructions
1. Fit the 4 motors into the chassis.
2. Solder the front left and rear left motor terminals together as one and connect it to the M1A and M1B terminals of the ESC (one for each terminal of the motor)
3. Solder the front right and rear right motor terminals together as one and connect it to the M2A and M2B terminals of the ESC (one for each terminal of the motor)
4. Solder an XT 60 connector to the ESC (+ to + and - to -)
5. Tape up all the joints with insulation tape to prevent shorts
6. Connect channel 2 on receiver to the left output of the ESC and channel 4 to the right.
## Radio Calibration
1. Go to setup->mixes->mix 1, set channel 2 as master and ch4 as slave, -100% for both positive and negative mix.
2. Go to setup->mixes->mix2, set ch4 as master and ch2 as slave, +100% for both.
3. Go to setup->reverse, and set ch4 for reverse on, rest off.

## Images
### 3D Model <img width="646" height="411" alt="image" src="https://github.com/user-attachments/assets/6a7fe7be-9a88-4e53-b6fb-91da495c0db2" /> 
### Wiring diagram <img width="889" height="668" alt="image" src="https://github.com/user-attachments/assets/2b86597b-ab33-47e9-8a4e-497790f89e1c" />

## BOM, With link to BOM.csv
# https://github.com/Sankarshan-T/Robo-Racer/blob/main/BOM.csv

| Component | Qty |	Price per item | Total Cost | Link |
| --------- | --- | -------------- | ---------- | ---- |
| Johnson Motors 12V 1000rpm | 4 | 280inr | 1120inr | [Link for Motors](https://ifuturetech.org/product/12v-1000-rpm-johnson-geared-dc-motor-grade-b/) |
| electocraze 20D ESC | 1 | 3200inr | 3200inr | [Link for ESC](https://www.technobotix.in/products/electrocraze-20d-bd-dual-channel-20amp-brushed-motor-controller/1781252000002857099) |
| Wheels | 4 | 150inr | 600inr | [Link for wheels](https://robu.in/product/65mm-robot-smart-car-12-rim-wheel-blue/?gad_source=1&gad_campaignid=20387462343&gclid=Cj0KCQiAoZDJBhC0ARIsAERP-F8owiACCQeQ3FbB1iGXmrpBKnK6DMTh9ymne9Y4ugNYVg9Mwty8RioaAnU_EALw_wcB) |
| Flysky FSi6X + receiver 6ch | 1 | 4900inr | 4900inr | [Link for transmitter + reciever](https://www.flyrobo.in/flysky-fs-i6x-2.4ghz-6ch-afhds-2a-rc-transmitter-with-fs-ia10b-2.4ghz-10ch-receiver) |
| LiPo battery 3s 2200mah	 | 1 | 1500inr | 1500inr | [Link for battery](https://robu.in/product/orange-2200mah-3s-30c60c-lithium-polymer-battery-pack-lipo/) |
| Chassis 3D printed | 1 | 300inr | 300inr | No Link |
| Solder | 1 | 80inr | 80inr | [Link for Solder](https://www.amazon.in/7Q7-Electronic-Soldering-50Grams-Solder-Wire/dp/B07ZLR38MB) |
| Tape | 1 | 15inr | 15inr | [Link for Tape](https://blinkit.com/prn/steelgrip-pvc-electrical-insulation-tape/prid/425578) |
| ---- | - | Total: | 11715inr | ---- |















