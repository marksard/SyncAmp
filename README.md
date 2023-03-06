# Synthesizer Sync Output Voltage Amplifier

A comparator-type amplifier that provides 5V Sync voltage for small instruments such as Teenage Engineering PO-32 and Paripi Destroyer.

[blog](https://marksard.github.io/2023/02/23/make-line-mixer/)

![img](https://marksard.github.io/assets/photos/20230222-P2220019.jpg)  
![img](https://marksard.github.io/assets/photos/20230222-P2220016.jpg)  

## Usage

Connect to SyncIn from a small instrument such as Teenage Engineering PO-32, Paripi Destroyer, etc.  
From Sync Out, connect to the instrument with Sync In.  
Adjust the Threshold knob until the LED flashes moderately in time with the pulse of the Sync voltage. If it syncs, you have succeeded.  

## Spec

### Input

3.5mm phone jack (TS)  
DC input is available.  

### Thresold Setting

As known as V ref.  
Range of values 0V to 2.5V.  

### Output

3.5mm phone jack (TS)  
Range of values 0V to 4.7V.  

### Power supply

- 9V

## Schematic

![img](https://marksard.github.io/assets/photos/comparator.jpg)  
