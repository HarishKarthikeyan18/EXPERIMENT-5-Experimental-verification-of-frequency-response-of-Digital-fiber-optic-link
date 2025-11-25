
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. Basically a fiber
optic link contains three main elements, a transmitter, an optical fiber and a receiver. The transmitter
module takes the input signal in electrical form and then transforms it into optical (light) energy
containing the same information. The optical fiber is the medium which takes the energy to the receiver.
At the receiver light is converted back into electrical form with the same pattern as originally fed to the
transmitter.

---

## PROCEDURE
▪ Refer to the block diagram & carry out the following connections and settings.
▪ Connect the power supply with proper polarity to the kit link-B and switch it on.
▪ Keep all Switch Faults in OFF position.
▪ Keep switch SW8 towards TX position.
▪ Keep switch SW9 towards TX1 position.
▪ Keep switch SW10 towards TTL position.
▪ Keep Jumper JP5 towards +5V position.
▪ Keep Jumpers JP6 shorted.
▪ Keep Jumper JP8 towards Pulse position.
▪ Feed TTL Square wave signal of 1KHz from the function generator to the IN post of
Digital Buffer.
▪ Connect the output post OUT of Digital Buffer to the post TX IN of Transmitter.
▪ Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector.
Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by
screwing it back.
▪ Connect the other end of the Fiber to detector SFH551V (Photo Transistor Detector) very
carefully.
▪ Observe the detected signal at post TTL OUT on oscilloscope.
▪ To measure the digital bandwidth of the phototransistor vary the input signal frequency and observe
the detected signal at various frequencies.
▪ Determine the frequency at which the detector stops recovering the signal. This determines the max.
bit rate on the digital link.
▪ Keep switch SW9 towards TX2 position.
▪ Keep Jumper JP7 towards +5V position.
▪ Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V (950nm). Do
not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the
cap. Now tighten the cap by screwing it back.
▪ Observe the detected signal at post TTL OUT on oscilloscope. 

---



## BLOCK DIAGRAM

<img width="525" height="302" alt="514896219-9aa4dd86-6fff-44b5-aee5-f7c4ee789b1a" src="https://github.com/user-attachments/assets/c9f5ff1f-6343-4ebb-8e40-0b5637be25aa" />
---






## TABULATION  
![20251117_164326](https://github.com/user-attachments/assets/435d3719-561b-44ec-9978-2087520888f9)


---

## MODEL GRAPH

![20251117_164352](https://github.com/user-attachments/assets/b406947a-a487-448b-88e5-389ba0c37648)

---

## RESULT

Thus, the frequency response of the digital fiber optic link was successfully verified. The system exhibited a stable response up to its cutoff frequency, beyond which the signal amplitude decreased due to attenuation. The measured bandwidth of the digital fiber optic link is approximately 200 kHz, confirming the expected performance characteristics of digital optical transmission.
