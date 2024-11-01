# Exercício 1
# Criando o conjunto 'frutas' e exibindo no console
frutas = {"maçã", "banana", "laranja", "uva"}
print("Frutas:", frutas)

# Exercício 2
# Adicionando 'morango' ao conjunto 'frutas'
frutas.add("morango")
print("Frutas após adicionar morango:", frutas)

# Exercício 3
# Removendo 'banana' do conjunto, verificando se existe antes de remover
if "banana" in frutas:
    frutas.remove("banana")
    print("Frutas após remover banana:", frutas)
else:
    print("Banana não está presente no conjunto.")

# Exercício 4
# Verificando se 'laranja' está no conjunto 'frutas'
if "laranja" in frutas:
    print("Laranja está no conjunto.")
else:
    print("Laranja não está no conjunto.")

# Exercício 5
# Criando o conjunto 'citrus' e unindo com 'frutas'
citrus = {"laranja", "limão", "tangerina"}
uniao = frutas.union(citrus)
print("União de 'frutas' e 'citrus':", uniao)

# Exercício 6
# Encontrando a interseção entre 'frutas' e 'citrus'
intersecao = frutas.intersection(citrus)
print("Interseção de 'frutas' e 'citrus':", intersecao)

# Exercício 7
# Encontrando a diferença entre 'frutas' e 'citrus'
diferenca = frutas.difference(citrus)
print("Diferença entre 'frutas' e 'citrus':", diferenca)

# Exercício 8
# Esvaziando completamente o conjunto 'citrus'
citrus.clear()
print("Citrus após esvaziar:", citrus)

# Exercício 9
# Convertendo 'frutas' em um conjunto imutável (frozenset)
frutas_imutavel = frozenset(frutas)
print("Conjunto imutável de frutas:", frutas_imutavel)

# Exercício 10
# Contando os elementos únicos no conjunto 'frutas'
print("Número de elementos únicos em 'frutas':", len(frutas))
