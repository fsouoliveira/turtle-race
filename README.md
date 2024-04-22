# turtle-race
Este código cria uma corrida de tartarugas usando a biblioteca Turtle do Python. Aqui está um resumo do que ele faz:

Importa as bibliotecas Turtle e Screen do módulo turtle, além do módulo random.
Define uma variável is_race_on como False, inicializando a corrida como desligada.
Cria uma tela com dimensões de 500x400 pixels.
Solicita ao usuário para fazer uma aposta em uma tartaruga, permitindo que ele insira a cor da tartaruga em que deseja apostar.
Define uma lista de cores e posições y para as tartarugas.
Cria seis tartarugas, uma para cada cor na lista de cores, posicionando-as em suas respectivas posições y.
Se o usuário fez uma aposta, define is_race_on como True, iniciando a corrida.
Enquanto a corrida estiver acontecendo (is_race_on é True):
Cada tartaruga se move uma distância aleatória para a frente.
Se alguma tartaruga ultrapassar a coordenada x de 230, a corrida é interrompida.
A cor da tartaruga vencedora é determinada e comparada com a aposta do usuário.
Uma mensagem é impressa indicando se o usuário ganhou ou perdeu a aposta.
