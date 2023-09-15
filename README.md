# Jogo_SEMNOMEAINDA
Tudo sobre o projeto



LINKS:

IMAGENS JOGO --------------------------------

https://picrew.me/en/image_maker/10948/complete?cd=DrQvz4IvCf

https://br.freepik.com/search?format=search&query=anime%20menino

https://www.istockphoto.com/br/search/2/image?family=creative&phrase=menino+anime

python
Copy code
import time

def intro():
    print("Bem-vindo ao Jogo RPG Simples!")
    print("Você está em uma floresta escura e precisa tomar uma decisão.")
    print("1. Seguir o caminho à esquerda.")
    print("2. Seguir o caminho à direita.")
    escolha = input("Digite 1 ou 2 para escolher o caminho: ")
    return escolha

def caminho_esquerda():
    print("Você escolheu o caminho à esquerda.")
    time.sleep(2)
    print("Você encontra uma fonte mágica que te dá poderes místicos!")
    print("Você se torna um feiticeiro poderoso e vive uma vida mágica.")
    print("Fim do jogo!")

def caminho_direita():
    print("Você escolheu o caminho à direita.")
    time.sleep(2)
    print("Você se depara com um dragão feroz!")
    print("Você tenta lutar, mas o dragão é muito forte e você é derrotado.")
    print("Fim do jogo!")

escolha = intro()

if escolha == "1":
    caminho_esquerda()
elif escolha == "2":
    caminho_direita()
else:
    print("Escolha inválida. Fim do jogo.")
