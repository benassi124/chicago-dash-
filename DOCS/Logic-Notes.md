## LEDs + Shift Light
On LED Logic, OxFF means that specific color is on when parameters are met 0x00 means LED is off:
### Configuring Shift Lights Using Compare Function
<img width="466" height="519" alt="image" src="https://github.com/user-attachments/assets/0b0b47f9-1dcb-4478-858a-87102caadf71" />


 Now I want to do another LED status in the event of Over Rev all 10 LEDs flash red.
Just add the following code. You might just need to change some of the COMPARE and TIM numbers, as they may already be taken.
 <img width="360" height="219" alt="image" src="https://github.com/user-attachments/assets/b743df26-98e0-40c0-9474-cd3e02477780" />



## How To Do Math
Any mathematics can be done through MATH field and then used in Dash Config.
**Example converting Km/H to MPH**
<img width="334" height="53" alt="image" src="https://github.com/user-attachments/assets/88fedcea-c145-4395-b636-6e6e7ade1011" />


## Alarm Logic
Oil Alarm
The internal algorithm uses an analog 0-10 bar sensor and a customizable RPM scale, which are important parameters for motorsports. Up to 16 RPM/pressure points can be configured. Yours is a bit simpler; it's easier for the algorithm to feed just two values: 0 - no oil pressure, and, say, 10 - there is oil pressure. Then the standard table that came with it will handle everything automatically. Now I'll write an example of logic for a dasheditor based on a discrete signal.
<img width="942" height="211" alt="image" src="https://github.com/user-attachments/assets/80e3bfc1-8656-47dd-b133-33d788a0b013" />

The editor allows you to load the required file from the DBC. The dashboard menu also has pre-installed ECUs that you can select. The only problem is, you may rarely have these ECUs or none at all, as markets vary. But adding what you need to ensure it works out of the box is no problem.
<img width="1008" height="561" alt="image" src="https://github.com/user-attachments/assets/ec0752f5-5c99-465f-af34-956ee2315daa" />
