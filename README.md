# Nomes-
Manipulando Nomes
def manipular_nomes():
   
    nome_completo = input("Digite seu nome completo: ")
    
    # Divide o nome completo em uma lista de nomes
    nomes = nome_completo.split()
        
    for posicao, nome in enumerate(nomes, start=1):
        num_caracteres = len(nome)  
        nome_invertido = nome[::-1]  
        
        # Exibe as informações formatadas
        print(f"\nNome {posicao}: {nome}")
        print(f"- Número de caracteres: {num_caracteres}")
        print(f"- Posição: {posicao}")
        print(f"- Invertido: {nome_invertido}")

if __name__ == "__main__":
    manipular_nomes()
