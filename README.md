# Maggie
A ai assistant that sits on your shoulder
Maggie can talk to you , answer to your quesion. 
It is controlled by Esp32 S3 and Xiaozhi is flashed into it.

Xiaozhi is an open-source AI chatbot framework built for ESP32 devices. It sends your voice to cloud-based language models instead of running them on the chip. The ESP32 records your voice over I2S and sends it over Wi-Fi to the Xiaozhi cloud, where the heavy work (speech-to-text, the AI model, text-to-speech) happens.

Major Components - ESP32-S3, two MEMS mics, a MAX98357A amp, a Li-ion charger with USB-C
