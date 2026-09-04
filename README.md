
# Yaesu-FTDX10-Junction-Box
Interface between rear connectors and some devices

Radio amateurs, especially those of us who enjoy building our own hardware, sometimes need to find solutions to connect our transceiver to other devices.

About a year ago, I acquired a Yaesu FTDX10. This transceiver has many connectors on the rear panel that allow interfacing with other devices, but the issue is that it’s often not just a simple pin-to-pin connection — additional electronic components are needed.

This box that I’ve built allows me to connect several devices:

* Activating the PTT for the QRM eliminator.
* Providing an audio output for a CW decoder.
* Using a push button for the external antenna tuner.

#### Schematic of the Junction Box
<img width="2048" height="1536" alt="WhatsApp Image 2026-09-04 at 17 44 18" src="https://github.com/user-attachments/assets/2ded80be-8ecf-44db-84f9-314eefaa9b52" />



  
<img width="1536" height="2048" alt="WhatsApp Image 2026-09-04 at 17 44 19" src="https://github.com/user-attachments/assets/af8d55ed-0577-46f6-85de-657dd0583b41" />
Hardware of the Junction Box

  
<img width="2048" height="1536" alt="WhatsApp Image 2026-09-04 at 17 44 18 (1)" src="https://github.com/user-attachments/assets/0d365a3d-c8cf-4dd2-a3ce-4e1a1619c077" />
Access to the Junction Box
  

## Activating the PTT for the QRM eliminator
As many of us know, our QTH is affected by local QRM. For this reason, I’ve acquired a QRM Eliminator to try to mitigate the effects of the noise. This device requires a PTT signal from the transceiver in order to switch between transmit and receive. The FTDX10 provides this signal through the RTTY/DATA connector.

## Providing an audio output for a CW decoder
I needed an audio output for the CW decoder built into my keyer. This output is not controlled by the volume, and therefore provides greater stability than, for example, the headphone output.


## Using a push button for the external antenna tuner
My antenna system includes an external automatic tuner to adjust the SWR on each band. When switching from one band to another, a carrier of less than 20 watts must be supplied to the antenna system so that the tuner can automatically adjust.

Every time I wanted to change bands, I had to reduce the power to 20 W and then increase it again to 100 W. With this interface, I’ve managed to make the FTDX10 transmit a carrier each time I press the tune button on the junction box, with a power level that I can adjust using the potentiometer that controls the ALC—saving me quite a bit of work and avoiding possible mistakes.

The power reduction via the ALC only takes place during the tuning process; afterwards, the transceiver returns to transmitting at the preset power level.


## Notes:
The potentiometer must be of 50K instead of 1M. (The images are before this modification).

The battery discharge current only occurs during the external tuner’s tuning process; therefore, I expect its lifetime will be several years.

