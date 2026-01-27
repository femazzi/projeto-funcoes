# 📊 Calculadora de Funções do 2º Grau

![Projeto de Matemática](https://img.shields.io/badge/Projeto-Ensino%20Médio-blue)
![Linguagem](https://img.shields.io/badge/Linguagem-JavaScript-yellow)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 📖 Sobre o Projeto

Calculadora interativa de funções quadráticas desenvolvida como projeto escolar na disciplina de Matemática do Ensino Médio. A aplicação permite visualizar graficamente funções do segundo grau e calcular suas principais propriedades matemáticas de forma didática e intuitiva.

## ✨ Funcionalidades

### 📐 Cálculos Matemáticos
- **Análise completa da função quadrática** (y = ax² + bx + c)
- Cálculo automático de:
  - Vértice da parábola
  - Raízes (zeros da função)
  - Delta (Δ)
  - Concavidade
  - Domínio e Imagem
  - Intercepto no eixo Y
  - Eixo de simetria

### 📈 Visualização Gráfica
- Gráfico interativo em tempo real
- Zoom in/out personalizado
- Reset de visualização
- Marcação visual de pontos especiais (vértice e raízes)
- Tooltips informativos ao passar o mouse

### 🎨 Personalização
- Escolha de cor personalizada para a linha do gráfico
- Interface responsiva e moderna
- Animações suaves e intuitivas
- Design dark mode com gradientes

### 💡 Modos de Entrada
1. **Entrada por coeficientes**: Digite valores individuais para a, b e c
2. **Entrada por função completa**: Digite a função inteira (ex: 2x^2 + 3x - 1)

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura da página
- **CSS3**: Estilização e animações
  - Flexbox & Grid Layout
  - Gradientes e efeitos glassmorphism
  - Animações e transições suaves
  - Design responsivo
- **JavaScript**: Lógica e interatividade
  - Manipulação do DOM
  - Cálculos matemáticos
  - Parsing de funções
- **Chart.js**: Biblioteca para renderização de gráficos

## 📋 Como Usar

### Opção 1: Entrada por Coeficientes
1. Insira os valores de **a**, **b** e **c** nos campos correspondentes
2. O gráfico e as propriedades serão atualizados automaticamente

### Opção 2: Entrada por Função
1. Digite a função completa no campo de texto (ex: `x^2 + 2x - 1`)
2. Formatos aceitos:
   - `x^2 + 2x - 1`
   - `2x^2 - 3x + 1`
   - `-x^2 + 4x`

### Controles do Gráfico
- **Zoom +**: Aumenta o zoom do gráfico
- **Zoom -**: Diminui o zoom do gráfico
- **Reset**: Volta ao zoom padrão
- **Cor da linha**: Clique no seletor de cor para personalizar

## 🎯 Fluxograma de Funcionamento

O projeto inclui um fluxograma detalhado (`Fluxograma-Funcoes.png`) que documenta toda a lógica de processamento da calculadora, desde a entrada de dados até a exibição dos resultados.

### Principais Etapas do Fluxo:
1. **Entrada de dados**: Captura dos coeficientes ou parsing da função
2. **Validação**: Verificação se é uma função quadrática válida (a ≠ 0)
3. **Cálculos**: Processamento de todas as propriedades matemáticas
4. **Renderização**: Atualização do gráfico e exibição das propriedades
5. **Interatividade**: Resposta às ações do usuário (zoom, mudança de cor, etc.)

## 📱 Responsividade

A aplicação é totalmente responsiva e se adapta a diferentes tamanhos de tela:
- 🖥️ **Desktop**: Layout em duas colunas (controles + gráfico)
- 📱 **Tablet**: Layout em coluna única com gráfico abaixo
- 📱 **Mobile**: Interface otimizada para telas pequenas

## 🎓 Conceitos Matemáticos Abordados

### Função Quadrática
```
f(x) = ax² + bx + c, onde a ≠ 0
```

### Propriedades Calculadas

1. **Delta (Δ)**: `Δ = b² - 4ac`
   - Δ > 0: duas raízes reais distintas
   - Δ = 0: uma raiz real (raiz dupla)
   - Δ < 0: sem raízes reais

2. **Vértice**: `V(xv, yv)`
   - `xv = -b / 2a`
   - `yv = -Δ / 4a`

3. **Raízes** (quando Δ ≥ 0):
   - `x = (-b ± √Δ) / 2a`

4. **Concavidade**:
   - a > 0: parábola voltada para cima
   - a < 0: parábola voltada para baixo

## 👥 Equipe de Desenvolvimento

**MovEx Development**

- Felipe Mazzi
- Gustavo Kyoshi
- Rafaela Candido
- Ryan Andrade

## 🚀 Como Executar

1. Clone este repositório ou baixe os arquivos
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Não requer instalação de dependências (Chart.js é carregado via CDN)

```bash
# Se estiver usando Git
git clone [url-do-repositorio]
cd [nome-do-projeto]
```

Depois, simplesmente abra o arquivo `index.html` no navegador.

## 💡 Exemplos de Uso

### Exemplo 1: Parábola Básica
```
a = 1, b = 0, c = 0
f(x) = x²
```
- Vértice na origem (0, 0)
- Concavidade para cima
- Uma raiz em x = 0

### Exemplo 2: Função com Duas Raízes
```
a = 1, b = -5, c = 6
f(x) = x² - 5x + 6
```
- Raízes: x = 2 e x = 3
- Vértice: (2.5, -0.25)
- Concavidade para cima

### Exemplo 3: Função sem Raízes Reais
```
a = 1, b = 0, c = 4
f(x) = x² + 4
```
- Sem raízes reais (Δ < 0)
- Vértice: (0, 4)
- Gráfico não toca o eixo x

## 🔧 Possíveis Melhorias Futuras

- [ ] Exportação do gráfico como imagem
- [ ] Histórico de funções calculadas
- [ ] Modo de comparação entre múltiplas funções
- [ ] Tabela de valores da função
- [ ] Cálculo de áreas sob a curva
- [ ] Suporte para funções cúbicas e polinomiais de grau superior
- [ ] Modo de aprendizagem com passo a passo dos cálculos

## 📄 Licença

Este é um projeto educacional desenvolvido para fins acadêmicos.

## 🙏 Agradecimentos

- Professores da disciplina de Matemática
- Biblioteca Chart.js pelos recursos de visualização
- Comunidade de desenvolvedores pelas ferramentas open source

---

**Desenvolvido com 💙 por estudantes do Ensino Médio**

*Projeto de Matemática - [Ano Letivo]*
