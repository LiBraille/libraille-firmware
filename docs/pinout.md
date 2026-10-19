Arquivo simples documentando qual pino do ESP32-C3 liga em cada lugar

# Pinagem do Hardware - ESP32-C3

- I2C SDA: GPIO 8 -> Placa PCA9685 (SDA)
- I2C SCL: GPIO 9 -> Placa PCA9685 (SCL)
- Botão Avançar: GPIO 2 (com Pull-Up interno)
- Botão Voltar: GPIO 3 (com Pull-Up interno)
- Botão Play/Pausa: GPIO 4 (com Pull-Up interno)
- Alimentação dos Servos: 5V externo via MT3608 + Capacitor 1000uF