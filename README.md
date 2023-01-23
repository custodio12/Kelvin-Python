# Projeto em __*Python*__ 💻
---
## Programa que simula compra de passagens de ônibus. 

O objetivo desse projeto foi desenvolver um algoritmo que possibilitasse a venda de assentos de ônibus. 

Como restrição, o programa deveria atualizar a matriz toda as vezes que fosse vendido, para que na próxima venda ele não aparecesse como disponível;
além de tratar inserções de valores incorretos ou de assentos não disponíveis para que o fluxo não seja interrompido. Após a finalização de simulação de compra, 
o algorítimo gera um arquivo no formato txt com a relação de todos os assentos vendidos e disponíveis.

Linguagem utilizada | Descrição do Projeto | Ferramenta 
---|---|---
<a href="https://www.python.org/">Python</a> | Simulador de compra de passagem de ônibus | <a href="https://www.jetbrains.com/pt-br/pycharm/">Pycharm</a>

- [x] Ao executar o `__main__`, o menu aparece conforme a tela abaixo:


     <img width="457" alt="Menu programa 1" src="https://user-images.githubusercontent.com/98350733/213193505-be2aa3e1-5282-4930-9ee1-0c7f1cfac517.png">
     

 - [x] Caso o usuário digite letra, espaço ou enter, a mensagem que aparece é a seguinte:
 
 
     <img width="443" alt="Erro de digitação" src="https://user-images.githubusercontent.com/98350733/213786308-a63ed058-fd8d-4e28-857a-985c92f97586.png">


- [x] Escolhendo a opção número 1, obtém-se o mapa de poltronas disponíveis:


     <img width="509" alt="Mapa de assentos" src="https://user-images.githubusercontent.com/98350733/213787233-85a3e105-dc2f-4b5c-a954-094737cd7d31.png">


- [x] Caso o usuário desista de escolher, e acidentalmente clique em uma letra, surge uma nova mensagem de erro, dando ao usuário apenas duas escolhas, encerrar o programa ou escolher uma poltrona. Escolhendo a opção zero (0) o programa é encerrado:


     <img width="445" alt="Encerrando sem escolha" src="https://user-images.githubusercontent.com/98350733/213788815-74b65a42-7d9c-4ab0-8eb6-8b3846051461.png">


- [x] No exemplo que segue, o usuário escolheu a poltrona 16. O código marca com um 'X' a poltrona escolhida e exibe a mensagem de reserva:


     <img width="425" alt="poltrona16" src="https://user-images.githubusercontent.com/98350733/214047590-5a882fe7-c1ef-455d-adbb-5f0d7316ddeb.png">
     

- [x] Caso o usuário tente escolher a mesma poltrona, surge a mensagem de erro 'poltrona está indisponível':


     <img width="452" alt="poltronaIndisponivel" src="https://user-images.githubusercontent.com/98350733/214048054-3223562e-1e9d-4d1f-80ea-a10a7fec535e.png">
     
     
 - [x] Por fim, após escolher a poltrona 16, o usuário encerra o programa digitando zero (0), e automaticamente é gerado um arquivo .txt informando como indisponível a poltrona 16, e disponível o que não foi escolhido durante a execução do programa:
 
 
     <img width="581" alt="FimDoPrograma" src="https://user-images.githubusercontent.com/98350733/214050347-4532d298-5330-4319-9b41-30302c59b684.png">
     <img width="541" alt="arquivoTxt" src="https://user-images.githubusercontent.com/98350733/214050384-ed1a4c5b-6395-4a70-b957-49c936420269.png">


 
 
     





