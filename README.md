
So for half life week three I'm building the tutorial project which is a MIDI Keyboard. I plan on giving it to my friend afterwards as a gift. For my keyboard I'm making a pcb and a 3d printable case. I'm useing the esp32s2 with a SN74AHCT125N and ads1115 for more IO pins. I added 5 touch keys which are piano keys, I did one encoder and two sliders with five swtiches and an LED for each switch. For my case I ended going with an open case because it's all I could manage at the moment but I think the case still turned out nice. And the pcb will screw into it.
[MIDI Keyboard.csv](https://github.com/user-attachments/files/33945325/MIDI.Keyboard.csv)"Reference","Qty","Value","DNP","Exclude from BOM","Exclude from Board","Footprint","Datasheet"
"D1,D3,D6,D9,D10","5","SK6812MINI-E","","","","LED_SMD:LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount","https://www.lcsc.com/datasheet/C5149201.pdf"
"D2,D4,D5,D7,D8","5","D","","","","Diode_SMD:D_SOD-123",""
"D11,D12","2","1N5819","","","","Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal","http://www.vishay.com/docs/88525/1n5817.pdf"
"J1","1","Conn_01x05","","","","mtpr:Untitled",""
"J2","1","Barrel_Jack_MountingPin","","","","Connector_BarrelJack:BarrelJack_Horizontal",""
"RV1,RV2","2","Slider","","","","Potentiometer_THT:Potentiometer_Bourns_PTA1543_Single_Slide",""
"SW1","1","RotaryEncoder_Switch_MP","","","","Rotary_Encoder:RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm",""
"SW2,SW3,SW4,SW5,SW6","5","SW_Push","","","","mtpr:Kailh Choc Low-Profile Switches",""
"U1","1","XIAO-ESP32-S3-DIP","","","","mtpr:XIAO ESP32-S3",""
"U2","1","ADS1115IDGS","","","","Package_SO:TSSOP-10_3x3mm_P0.5mm","http://www.ti.com/lit/ds/symlink/ads1113.pdf"
"U3","1","SN74AHCT125N","","","","mtpr:DIP794W45P254L1930H508Q14",""


<img width="641" height="557" alt="Screenshot 2026-10-25 214404" src="https://github.com/user-attachments/assets/7720e8f5-ca8a-4385-b348-8e192d960c64" />
<img width="931" height="670" alt="Screenshot 2026-10-25 220921" src="https://github.com/user-attachments/assets/041f5538-e97d-46fb-9450-ea74141d1ab5" />
<img width="413" height="356" alt="Screenshot 2026-10-25 221736" src="https://github.com/user-attachments/assets/463fca9b-f833-495b-9dbb-9c888c5154f1" />
<img width="640" height="517" alt="Screenshot 2026-10-25 231634" src="https://github.com/user-attachments/assets/d8f4d449-9584-4c55-b68e-b7d3b2a3f9f2" />
