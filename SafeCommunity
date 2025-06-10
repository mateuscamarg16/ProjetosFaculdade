import os
def exibir_nome():
    print('Safe Community')

usuarios = [ 
    {'nome': '', 'email': '', 'senha': ''}
    ]

def login():
    os.system('cls')
    email = input('Informe seu e-mail: ')
    senha = input('Informe sua senha: ')

def criar_cadastro():
    nome_usuario = input('Digite o seu nome: ')
    email_usuario = input('Informe seu e-mail: ')
    senha_usuario = input('Crie uma senha: ')
    dados_do_usuario = {'nome':nome_usuario, 'email': email_usuario, 'senha': senha_usuario}
    usuarios.append(dados_do_usuario)

def voltar_menu_principal():
    input('\nDigite uma tecla para voltar ao menu principal! ')
    main()

def exibir_subtituto(texto):
    os.system('cls')
    print(texto)
    print()

def definir_usuario(): 
    usuario = input('\nVocê possui cadastro? ')  
    
    if usuario == 'Sim':
        exibir_subtituto('Efetuar login')
        login()
    else:
        exibir_subtituto('Criar conta')
        criar_cadastro()
        print('Cadastro realizado com sucesso!')
        voltar_menu_principal()
                

def main():
    exibir_nome()
    definir_usuario()

if __name__ == '__main__':
    main()
