# Guia de comandos básicos linux para funcionários:

comandos = {
    "ls": "lista arquivos e diretorios",
    "cd": "altera o diretorio atual",
    "pwd": "mostra o caminho do diretorio atual",
    "mkdir": "cria um novo diretorio"
}

entrada = input().strip()

# Usa get para resolver direto
print(comandos.get(entrada, "comando invalido"))

