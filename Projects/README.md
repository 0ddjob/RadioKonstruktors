# Operating Principles & Schematics (Принцип Работы И Выполнение Схем) 
(Translation in progress!)
## ГНЧ Project 5.1: Low Frequency Generator (Генератор Низкой Частоты)
The low frequency generator can be used to test low frequency amplifiers.<br>

The low-frequency generator consists of two stages. The first stage, assembled on transistor T1, is the generator itself, the generation frequency of which is determined by elements R1, R2, C1, C2, C3. The generated signal is amplified by transistor T2 and through resistor R8 enters the circuit under study.<br>

On the circuit board, assemble the low-frequency generator and amplifier according to the diagrams in Fig. 1-3, 1-1.<br>

After assembly, check the connections of the elements, their ratings according to the circuit diagrams. Turn on the power and hear sound vibrations in the speaker.<br>

## У1 Project 5.2: Amplifier I (Усилитель I)
Amplifier I is designed to amplify speech and music signals. The amplifier is assembled on three transistors. The first stage on transistor T1 is a preamplifier. The second stage on transistors T2 and T3 is a push-pull output stage.<br>

The amplifier is powered by a 9V "Krona-VC" (Крона-ВЦ) battery. Assemble the amplifier according to Fig. 1-2, 1-3. Amplifier I can be tested using a low-frequency generator. The amplifier is easy to manufacture and does not require additional adjustment if assembled correctly.<br>

## У2 Project 5.3: Amplifer II (Усилитель II)
Amplifier II is designed to amplify weak signals. The amplifier is assembled with four transistors. The first stage is assembled with transistor T1, it provides the ability of the amplifier to respond to weaker signals than Amplifier I. The second and third stages, assembled with transistors T2-T4, represent the amplifier given in Section 5.2.<br>

The amplifier assembly is carried out according to Fig. 2-1, 2-2. The Amplifier II can be tested using the low-frequency generator assembled earlier.<br>

## ПР Project 5.4: Sampler (Пробник)
The probe is designed to check the high-frequency and low-frequency paths of a transistor radio receiver.<br>

The probe consists of a detector and an amplifier. The detector is made on the elements C1, Д1, Д2, R1, C2. The amplifier circuit is similar to that shown in Fig. 2-1.<br>

An amplitude-modulated signal is fed to the detector input. Diode Д2 passes the positive half-wave of the modulated signal, diode Д1 cuts off the negative half-wave. The high-frequency component of this signal is shorted to the case through capacitor C2, and the low-frequency part of the signal (sound) is isolated on load R1, goes to the amplifier and sound vibrations will be heard in the loudspeaker. The probe can be checked using a low-frequency generator, for which the generator output must be connected to (-) capacitor C3. Sound vibrations should be heard in the loudspeaker. The detector part of the probe is checked for correct connections. The probe can be used to check the high-frequency part of any industrial transistor.<br>

The probe is assembled according to Fig. 3-1, 3-2.<br>

## КМ Project 5.9: Morse Key (Ключ Морзе)
The Morse key diagram is designed for learning Morse code.<br>

Morse code consists of dots and dashes. A dot is transmitted by a short press of the key, and a dash by a long press of the key.<br>

The Morse key consists of a rectangular pulse generator and an amplifier. The pulse generator is assembled on transistors T1 and T2 according to the multivibrator circuit. From the generator output, pulses are fed to the amplifier input. <br>

The amplifier is described in section 5.2 of this manual.<br>

Assembly is performed according to Fig. 8-1, 8-2.<br>

Set the variable resistor slider clockwise until it stops. Each time you press the key lever, you will hear a sound signal in the speaker.<br>

## РВ Project 5.10: Time Relay with Adjustment (Реле Времени С Регулировкой)
Designed to generate time delays of different durations.<br>

The time relay circuit consists of a rectangular pulse generator (multivibrator) assembled on transistors T2 and T4, a power amplifier assembled on transistors T5-T7, and a timer assembled on transistors T1 and T3. This circuit differs from the Morse key circuit by introducing a timer. In this circuit, it is possible to adjust the switching on of sound vibrations relative to the moment of switching on the power supply. For this purpose, a resistor R1 with a resistance of 300KΩ to 1MΩ can be installed in the circuit.<br>

With a resistor R1 resistance 1MΩ, the delay is approximately 30±6 seconds.
- R1 = 680KΩ ... 20±5s
- R1 = 470KΩ ... 12±4s
- R1 = 300KΩ ... 9±3s

Assembly is carried out according to Fig. 9-1, 9-2.<br>
