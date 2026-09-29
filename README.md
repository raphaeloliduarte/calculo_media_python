# Minha Apresentação

## Tecnologias Utilizadas

- Python 3

## Cálculo de Média

Projeto desenvolvido em Python para calcular a média de duas notas e informar se o aluno foi aprovado ou reprovado.

```python
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2

print("=== Sistema de Notas do Aluno ====")

n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")
```
## Como Instalar e Executar
Entre na pasta do projeto:

cd sistema-notas

Execute o programa:

python notas.py

No Linux/macOS, caso necessário:

python3 notas.py

Exemplo de Uso
=== Sistema de Notas do Aluno ====
Digite a primeira nota: 8
Digite a segunda nota: 6
A média final é: 7.00
Status: APROVADO!

Regra de Aprovação
Média maior ou igual a 7,0: APROVADO

Média menor que 7,0: REPROVADO

Estrutura do Projeto
sistema-notas/
└── notas.py

Projeto Autoral
Projeto desenvolvido por Raphael de Oliveira.

Contato
LinkedIn: linkedin.com/in/raphaeloliduarte

GitHub: github.com/raphaeloliduarte