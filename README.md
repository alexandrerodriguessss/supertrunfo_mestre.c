
# 🃏 Comparador de Cartas de Cidades Brasileiras – Super Trunfo em C

Projeto desenvolvido como parte da disciplina **Introdução à Programação de Computadores** na Estácio, sob orientação do professor **Sérgio Cardoso**.

Inspirado no clássico Super Trunfo, o sistema compara atributos de duas cidades brasileiras e determina qual carta vence em diferentes critérios.

---

## 📌 Funcionalidades

- Entrada interativa de dados para duas cidades
- Cálculo automático de:
  - Densidade populacional
  - PIB per capita
  - Inverso da densidade (superpoder)
- Comparações entre atributos selecionados pelo jogador
- Exibição de vencedores individuais e da soma final
- Tratamento de empates
- Menus dinâmicos com prevenção de escolhas repetidas
- Exibição final da carta vencedora

---

## ⚙️ Como Compilar e Executar

### ✅ Compilação

No terminal (Linux/Mac) ou CMD (Windows):

```bash
gcc main.c -o comparador
```

### ▶️ Execução

```bash
./comparador
```

---

## 🧪 Exemplo de Uso

Após executar o programa, o sistema solicitará os dados de duas cidades:

```text
-----------Carta 01-----------
Digite o Estado?: Pará
Digite o Código?: PA
Digite o nome da cidade?: Belém
Qual a População?: 1506420
Qual é a Área (em km²)?: 1059458.4
Digite o PIB(em bilhões de reais): 126.8
Número de pontos Turísticos?: 22
```

Depois para a segunda carta (ex: Amazonas / Manaus) e então:

```text
-----------MENU DE COMPARAÇÃO-----------
Escolha dois atributos diferentes:
1. População
2. Área
3. PIB
4. Pontos turísticos
5. Densidade demográfica (menor vence)
6. PIB per Capita
Digite a opção 1 (1 a 6): 3
Digite a opção 2 (1 a 6): 5
```

---

## 🧠 Conceitos Aplicados

- Entrada de dados com `scanf`
- Manipulação de strings (`char[]`)
- Estruturas de decisão (`if`, `else if`, `else`, `switch`)
- Operadores lógicos e relacionais
- Operador ternário
- Estruturas encadeadas e aninhadas
- Formatação com `printf`

---

## 🎓 Professor Responsável

**Sérgio Cardoso**  
Disciplina: *Introdução à Programação de Computadores*  
Estácio – Análise e Desenvolvimento de Sistemas

---

## 📹 Apresentação em Vídeo

> (Adicione aqui o link para o seu vídeo no LinkedIn ou YouTube)

---

## ✍️ Autor

Alexandre Rodrigues  
Estudante de Análise e Desenvolvimento de Sistemas  
Apaixonado por programação e sempre em evolução 🚀
