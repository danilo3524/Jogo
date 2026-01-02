
print('1. ir para floresta')
print('2. ir para o galpão')
print('3. sair do jogo')

escolha = int(input('escolha uma da opção: '))

if escolha == 1:
    print('floresta sem perigo')
    
elif escolha == 2:
    print('galpão sem perigo o que deseja fazer')
    print('1. ir silenciosamente')
    print('2. um ataque fatal que acaba com os inimigos')
    
    b = int(input('escolha uma opção: '))
    
    if b == 1:
        print('irá demorar um pouco e você ficará com pouca vida para avançar')
    elif b == 2:
        print('escolha com sucesso, todos os inimigos aniquilados')
else:
    print('saindo do jogo')

