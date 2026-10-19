# libraille-firmware
Firmware em C++ para ESP32-C3: controle dos 6 micro servos via PCA9685 e leitura serial/LittleFS.

```
libraille-firmware/
├── src/
│   └── libraille_firmware.ino   # O código principal que sobe na placa
├── docs/
│   └── pinout.md                # O mapa elétrico (onde cada fio liga no ESP32)
├── .gitignore                   # Ignora arquivos temporários de compilação
└── README.md                    # Passo a passo de como gravar o código na placa
```

Firmware é simplesmente o programa que fica gravado dentro da memória do microcontrolador (o ESP32-C3) para fazê-lo funcionar como um aparelho independente.

Se você ligar o ESP32-C3 na tomada sem nenhum código, ele é apenas uma placa de silício inerte. O firmware é o "cérebro" que ensina o circuito a ler os cliques dos botões físicos e girar os motores certos.