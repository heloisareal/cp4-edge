# CP 4 ARDUINO
- Heloísa Real 554535
- Eduardo Dallabella 556803
---------
### Materiais Utilizados
- Materiais físicos utilizados:
- Arduino
- Protoboard
- 4 jumpers macho e fêmea
- Sensor ultrasônico
- Fonte Arduino
- Extensor fonte arduino

### Organizando o ambiente
- Primeiramente instalamos (node-red-dashboard) para vizualizar graficamente os elementos, e o (node-red-node-serialport), para a conexão com o arduino.

### Descrição do Projeto
- Iniciamos no cmd, abrindo o nodered e instalando as dependências. Após isso, iniciamos a montagem, escolhemos duas cidades de São Paulo, Jarinú e Bragança Paulista para analizarmos os dados.
- O projeto em sua etapa final, ficou dessa maneira:
![image](https://github.com/user-attachments/assets/6e591fa0-421a-4fe0-8e07-98631a64c1f4)
- Cada conexão representa uma etapa do envio de dados da API para a exposição gráfica dele.

### Arduino
- Para fazer a distância do arduino, após o download do pacote de serialport, adicionamos um serial in, com o nome de COM5, e conectamos com gauge de distância para apresentar de forma gráfica no dashboard, ficando dessa forma;
![image](https://github.com/user-attachments/assets/dbee599c-d98e-44ea-b863-7f099e70eb58)
- Resultado no debug:
![image](https://github.com/user-attachments/assets/e2d99eb4-385f-43d3-93dc-d9f32b9ffbdd)
- Imagem circuito físico:
![WhatsApp Image 2024-08-30 at 22 27 48](https://github.com/user-attachments/assets/2d514c97-3bd7-4749-abe5-8734be829e16)


### Código Fahrenheit
- Para apresentar a temperatura em Fahrenheit adicionamos uma função entre o json e temperatura 
![image](https://github.com/user-attachments/assets/eb529d90-427d-4a3e-aa8e-c00b93034215)


### Resultados Finais
- A apresentação gráfica do dashboard ficou organizada e bem didática!
- Acompanhe o menu para vizualizar os resultados:
![image](https://github.com/user-attachments/assets/23c3fff1-9f4e-46f0-89e8-e269565e073e)
![image](https://github.com/user-attachments/assets/a894eb7b-83f0-4998-8845-b4c190116456)
![image](https://github.com/user-attachments/assets/1cc175e7-28b8-4055-ae1e-5abcf0083c7b)
