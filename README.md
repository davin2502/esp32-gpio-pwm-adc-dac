# Dasar Pemrogaman ESP32 Untuk Pemrosesan Data Input/Output Analog dan Digital (GPIO, PWN, ADC dan DAC)

## Alat dan Bahan
1. ESP32
2. Arduino IDE
3. Projectboard
4. Kabel Jumper
5. Resistor < 220Ω
6. LED (5)
7. Push Button (3)
8. Potensiometer

## Instalasi Board ESP32 di Arduino IDE
- Masuk ke Preferences
- Isikan board url dengan link : https://dl.espressif.com/dl/package_esp32_index.json dan simpan
- Buka Tools > Board > Boards Manager
- Cari ESP32, by Espressif. Kemudian instal
- Pilih flash mode DIO/QIU menyesuaikan
- Jika terdapat error saat uploading, tekan dan tahan tombol Boot pada ESP32 saat upload, hingga Connecting selesai

## Percobaan GPIO
### Gambar Rangkaian GPIO 1
![](https://i.imgur.com/FDqWGY0.png)
### Hasil Percobaan GPIO 1
![](https://camo.githubusercontent.com/09cbec9a49a29af09558d389671db77c5458d80042f79fe3057c8d63db3e6650/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333436333433353737353635353933362f4750494f312e676966)

### Gambar Rangkaian GPIO 2
<img src="https://camo.githubusercontent.com/001fa5ca7b0de55d60c49c5cd82ee0af9b01fc1222397401b84311e5a396f730/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333438303436363135393834313337302f4750494f322e706e67" width=425px>

### Hasil Percobaan GPIO 2
![](https://camo.githubusercontent.com/b9e063ff0995f0c08c6d16637637cc44edb84f4299c9030713ad7894521ff64f/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333436333433363535313538393930382f4750494f322e676966)

### Gambar Rangkaian GPIO 3
<img src="https://camo.githubusercontent.com/189bbb22ec02a6d2a3aee8d3527edd3246ee87bf5db46a38604b750af190a7c4/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333438303436353836363233353937352f4750494f332e706e67" width=425px>
### Hasil Percobaan GPIO 3
![](https://camo.githubusercontent.com/1121dda14e1c8838bf870cd859cfc645105842e49cb48ab29c62148afa4f6980/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333436333433363139353037383135352f4750494f332e676966)

## Percobaan PWM
### Gambar Rangkaian PWM 1
<img src="https://camo.githubusercontent.com/76ccf78c517d8a93655e6f7727712f9ae1c9b228c08861df6899f9c193c397e0/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333439373635343638313836363234302f50574d312e706e67" width=425px>
### Hasil Percobaan PWM 1
![](https://camo.githubusercontent.com/e54d4259b96b9088d7310aced18c8fca3cd7b8476d0fc3519b1ccc62336d063b/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333532353433363734303734373334342f50574d312e676966)

### Gambar Rangkaian PWM 2
<img src="https://camo.githubusercontent.com/6d8cefa29d9255fad25cfdbb7e67e24430d2fe54dd547aa213cb326d4096cc37/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333439373635343335343730363439342f50574d322e706e67" width=425px>
### Hasil Percobaan PWM 2
![](https://camo.githubusercontent.com/c0a9be8ed7f449a1edd59cc0ae2afd9351d63ca593f8f4bef08ac0e31119ed2e/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333532353433363332353530373038322f50574d322e676966)

## Percobaan ADC dan DAC 
### Gambar Rangkaian ADC dan DAC 1
<img src="https://camo.githubusercontent.com/ce27918d69ecf2956392d794c59f4aabbf798826ede7b3cf631497a1fc08a43f/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333531323232343035333938353431302f414443312e706e67" width=425px>
### Hasil Percobaan ADC dan DAC 1
![](https://camo.githubusercontent.com/1b1bb61ff6f95cb22f21a31d95bc5f3740cb2f6380e4daa6bfef75e5773d6dbc/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333531343736323437313933313938342f414443312e676966)

### Gambar Rangkaian ADC dan DAC 2
<img src="https://camo.githubusercontent.com/93699b9069d68fc511ea354f7d6c793542ed18ac59f90da5038873eb9e9edbff/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333531323232343339333732383039312f414443322e706e67" width=425px>
### Hasil Percobaan ADC dan DAC 2
![](https://camo.githubusercontent.com/6bab798cc933e1c7e320afe4d7aaa65218342d6d3dfd49e1272967a33df25bce/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034333532363033363439363836333336322f414443322e676966)
