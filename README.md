# ESP32_TagoIO

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/871cbd90-267d-4ade-98a0-704c075542bc)

Exemplo de código mínimo para publish e subscribe em tópicos MQTT utilizando o broker da TagoIO.

Primeiro passo é a criação de um dispositivo, para isso crie um dispostivo do tipo MQTT. No meu exemplo ele será chamado de Random

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/f9938d66-7ab2-4a63-8532-ab83f8a34f15)

Encontre o seu Token, pois será necessário para o firmware.

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/4a192696-3993-4408-9177-28450f19d346)

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/d99a8500-2e60-413c-a5df-5a352876fd47)

Para você criar intereções você deve:

Criar um action para RECEBER as informações:

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/2edf1ede-fbad-482c-8845-bd82bb98716e)

Criar um action para ENVIAR as informações:

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/1eeed2e7-0ba5-44fb-bb6b-87c31f8cf68b)

Você deve criar dois action um para enviar 0 e outro para enviar 1.

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/61b7f4f1-9ed8-4158-be8e-44975560630f)

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/ccd1e68a-9c5c-497c-90ee-eaa0dcb37fe7)

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/18239206-208e-44b4-af99-39e504e8a65c)

A variável que será observada será a state_button.

A criação da variável é apartir do JSON enviado, de acordo com o firmware.

![image](https://github.com/VictorRavani/ESP32_TagoIO/assets/101602056/13e65349-f9c8-4324-b0af-a90b6c387981)
