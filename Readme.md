## Um pouco de código para me apresentar

```python
def sobre_mim():
    nome = "Seu Nome"
    linguagens = ["Python", "HTML", "JavaScript"]
    interesses = ["Desenvolver soluções", "Aprender novas tecnologias", "Projetos open-source"]

    print(f"Olá, eu sou {nome}!")
    print("Aqui estão algumas das minhas linguagens favoritas:")
    for linguagem in linguagens:
        print(f"- {linguagem}")
    print("Meus interesses incluem:")
    for interesse in interesses:
        print(f"- {interesse}")

sobre_mim()

