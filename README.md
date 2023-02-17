# Components

### O que é um Componentes ? 
Partes do código de nossa aplicação que ficam isolados, separados, são indepedentes.<br>
Esses elementos são isolados possuem um JavaScript, HTML  e CSS própios.

## Diferenças para a instância VUE principal

Propriedade `data` é uma função  e deve  retornar um objeto.<br>
Quando trabalhamos com um component a propriedade `data` vira uma função como descrito no código abaixo.

```
data() {
    return {
        name: 'Vue Components'
    }
}
```

### Maneiras de Criar 

- Componente Global
- Componente Local
- Componentes  atráves do VUE-CLI (Single File Components)

# O que é o vue-cli ?

Sistema para desenvolvimento  de aplicações  em VUE.JS. Ferramenta que nos ajuda  a criar um projeto  VUE.js  em poucos minutos. 

  ## Intalação
  Podemos baixar  o vue-cli de duas maneiras  principais:

  - npm
  ````
  npm install -g @vue/cli
  ````
  - yarn

  ````
  yarn global add @vue/cli
  ````
  # Estrutura de Pastas Padrão

  - \public <br>  
  Pasta que contem o arquivo `index.html` que o     
  navegador irá interpretar.

  - \src\assets <br>
  Pasta que contém os arquivos de estilo e bibliotecas de terceiros (CSS, Imagens, etc.)

  - \src\assets <br>
  Pasta que contém os componentes que iremos usar no projeto.

  - \src\App.vue <br>
  Primeiro componente da aplicação. É o que é chamado por padrão.

  - \src\main.js <br>
  Arquivo JS que cria a instância VUE chama o primeiro componente e monta nossa aplicação

<br>

# O que são PROPS ?

São maneira de informar dados para um componentes, criamos as props na instâncias  VUE (camelCase).

Podemos informa-los  para os componentes assim como o atributo do HTML (kebab-case).

## Exemplo Básico

````
<component name="Foot" age="25"><component/>

export default {
    props:['name', 'age']
}
````

## Validação
É possivel fazer uma validar os dados  que iremos  informar nas props (tipo de dado, se a prop é obrigatória, etc..).

Para isso , é necessário  aprimorar um pouco mais  a propriedade `props`.

````
<component person-name="Evan Daniels" :age="idade"><component/> -> Usamos padrão kebab-case

export default {
    props: {
        personName: String, -> Usamos o padrão camelCase
        age: {
            type: String,
            required: true 
        }
    } -> Se possivel , sempre use esse padrão.
}
`````
## Possível validações de de tipo

- String
- Number 
- Boolean
- Array
- Object
- Date
- Function
- Symbol

`PROPS`: Em muitos casos , é necessário  informar as `props` junto com a diretiva `v-bind`.
Fazemos isso  quando precisamos informar  uma propriedade instancia  `VUE` ou uma expressão `JavaScript`.

`EXEMPLOS`
````
<components v-bind:list="[1,2,3]"><components/>
<components v-bind:color="variavel"><components/>
```` 