# Prova---Dicionarios-e-Sets-


# Crie um dicionário que irá armazenar informações de um contato, 
# incluindo o nome, o telefone e o email. Peça ao usuário para fornecer esses dados, 
# solicitando que ele insira o nome do contato, o número de telefone e o endereço de email. 
# Após coletar todas as informações necessárias, exiba o conteúdo do dicionário, 
# mostrando todas as informações do contato inserido pelo usuário.


contato = {}
 
contato['nome'] = input("Digite o nome do contato: ")
contato['telefone'] = input("Digite o número de telefone do contato: ")
contato['email'] = input("Digite o endereço de email do contato: ")


print("\nInformações do contato:")
for chave, valor in contato.items():
    print(f"{chave.capitalize()}: {valor}")
