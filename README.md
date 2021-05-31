# Desenvolvedor Fullstack com foco em mobile

O teste tem como objetivo obter uma base do seu conhecimento em algumas linguagens específicas. Não existe apenas uma solução para as questões, portanto aplique suas próprias ideias e soluções. Você poderá consultar a internet como em qualquer ambiente real de desenvolvimento, mas não use Ctrl+C e Ctrl+V, pois questionaremos a solução das questões.

Você poderá entregar o teste em uma das seguintes formas:
- Arquivo compactado;
- Link para o GitHub com as soluções.

## Javascript :blue_car:

**1. Quantas vezes o caractere ocorre?**

Complete a função para que ela retorne o número de vezes que o caractere ocorre em determinada frase.

```javascript
function buscarVezesLetra(letra, frase) {
	return
}

buscarVezesLetra('n', 'Quantas vezes essa letra ocorre nesta frase?') // Esperado 2
buscarVezesLetra('e', 'Quantas vezes essa letra ocorre nesta frase?') // Esperado 7
```

**2. Mescle 2 arrays com valores duplicados.**

Complete a função para que ela aceite 2 arrays de números e retorne 1 mesclado, filtrando itens duplicados.

```javascript
function mesclarArrays() {
	return
}

mesclarArrays([1, 2, 3], [3, 4, 5]) // [ 1, 2, 3, 4, 5 ]
mesclarArrays([-10, 22, 333, 42], [-11, 5, 22, 41, 42]) // [ -11, -10, 5, 22, 41,  42, 333]
```


**3. Conserte o caos entre estas strings.**

As strings de exemplo estão misturadas. Complete a função para que ela retorne as strings organizadas.

```javascript
function organizar() {
	return
}

organizar('java', 'tpi%rcs') // Javascript
organizar('c%ountry', 'edis') // Countryside
organizar('down', 'nw%ot') // Downtown
```

**4. Calcule o tempo em dias.**

Escreva um algoritmo que calcule o tempo em dias a partir de uma data inicial e final
recebidos no formato dd/mm/aaaa (string). Não deve usar plugins como moment ou date-fns.

```javascript
function calcularDiferenca(dataInicio, dataFinal) {

}

calcularDiferenca("10/05/2021", "15/05/2021") // Esperado 5
```

## React :airplane:

**5. Atualizando dados na tela**

Crie um formulário simples com campos para nome e idade. Informe o valor dos componentes na tela, tornando os campos do formulários reativos. Preferencialmente, use Reack Hooks.

Exemplo:

![Peek 31-05-2021 10-36](https://user-images.githubusercontent.com/83364092/120201738-29ac2900-c1fc-11eb-9045-e0ff683d8360.gif)

**6. Dados do repositório do GitHub**

Crie um formulário de pesquisa que consuma a API aberta do GitHub. A pesquisa deve buscar os dados de um repositório e exibir em tela. Procure exibir o máximo de informações importantes, da forma mais organizada possível.

Exemplo:

![Peek 31-05-2021 11-18](https://user-images.githubusercontent.com/83364092/120206824-0ab09580-c202-11eb-938e-895fb7aa8362.gif)

**7. Todo app**

Replique o gerenciador de tarefas a seguir:

![Captura de tela de 2021-05-31 11-30-49](https://user-images.githubusercontent.com/83364092/120208313-b8707400-c203-11eb-8b13-cfffefda53bf.png)

- Você pode usar o Bootstrap se preferir;
- Procure manter o visual o mais parecido possível;
- Procure tornar o app o mais funcional possível.

## React Native (diferencial) :rocket::rocket::rocket:

**8. Dados do repositório do GitHub**

Execute a mesma funcionalidade do exercício 6 em um app com React Native.
