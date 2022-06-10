#HTML 
- HyperText Markup Language

- Hiper texto?
- Marcação
 - Tags
  -atributos
- Linguagem
 - maneira de escrever

O que é Hypertext?
o que é markup?
O que é tag?
O que é linguagem HTML?

CSS
- Apresentação visual para o cliente
- Estilos para HTML
- Cascading Style Sheets (folha de estilo em cascata)

# Declaração
- seletor
- Propriedade e valor

# Conceitos
- cascata (sempre considera o último que for colocado)
- especificidade (tag - 001; id - 100 (mais específico)) 
- box model (Tudo são caixas; caixas possuem determinadas propriedades: 
margin (espaços ao redor de uma caixa); borda (borda de uma caixa); 
padding (preenchimento ); content (conteúdo que terá altura e largura))


JAVASCRIPT

- é uma linguagem de programação interpretada e executada pelos 
navegadores
- a inteligência da tríade (HTML é a estrutura, CSS é a beleza e 
JS é a inteligência)
- Não é JAVA, embora o nome seja semelhante, são linguagens diferentes

# Por que JS?
- aplicativos --> para WEB, desktop (Electron) e mobile (Reactive native)
- Empresas famosas --> Instagram, Google, Netflix, TikTok...
- Moderna e viva --> comunidade e linguagem que cresce cada vez mais 

1. VARIÁVEIS
- let (pode alterar valor) estaChovendo = true
const (não pode alterar valor) meuNome = "Mayk"

estaChovendo = false
console.log(estaChovendo)


2. TIPOS DE DADOS
- String (o texto)
- ""
- ''

NUMBER
- 12 - integer (+ -)
- 3.2 - float (+ -)

BOOLEAN
- true ou falso
- const maiorDeDezoito = false

UNDEFINED
- indefinido (não existe)

3. OPERADORES
- atribuição (ex: =)
- atribui valor 
- let n1 = 12
- let n2 = 3

Aritméticos (ex: * / + -)
Cálculos matemáticos simples

concatenação de string (+)
("23" + 4 + "abc")

Comparação (ex: > < ==)
Transforma a expressão em true ou false
const maiorQue = 1 > 2 // false
const igualA = 1 == 1 // true

4. CONDICIONAL (if/else)
const idade = 17
const maiorDeDezoito = idade >= 18

- if (maiorDeDezoito) {
  alert ("pode tirar carteira de motorista")
}

- else {
  alert ("não pode tirar")
}

5. ESTRUTURA DE DADOS
- Array - vetor - lista
- array ---               0   1     2  3
- const temperaturas = [23.3, 32.2, 1, 5]
console.log(temperaturas[0]) --> irá mostrar o 23.3

OBJECT
const pessoa = {
  nome: "Mayk"
  idade: 38,
  filhos: ["K", "E", "J", "L", "G"]
}
console.log(pessoa.filhos[2])

6. FUNCTION
 1. Criação
    - function nomeDaFuncao () {
      console.log('código dentro da função')
    }
  
  2. Execução
    - nomeDaFuncao()

  - Parâmetros
  - function soma(a, b) {
    console.log(a + b)
  }
  soma(34, 45)
  soma(90, 54)

  - Retorno
  function soma(a, b) {
    return a + b
  }

  const multiplica = soma(2, 2) * 4
  console.log(multiplica)

  console.log(soma(2, 2))

7. EXTENSÕES DA LINGUAGEM (ex.: Math, Date ...)
- Math.random()
- Math.floor(1.2) - arredonda para baixo
- Math.ceil(1.2) - arredonda para cima
- Math.PI() - número do PI

8. DOM - Document Object Model 
- window
- window.alert("alerta")
- document
- document.write("texto")
- manipular elementos
- document.documentElement.style.background = "black"
