---
sidebar_position: 1
---
# Code

## Comment faire

[language](#language-de-programmation-accepter)\
[attribut](#attribut)

````md
```{language} {attribut}
// Ecrire le language
```
````

## Attribut

| Attribut        | Description                              | Exemple                             |
|-----------------|------------------------------------------|-------------------------------------|
| live            | faire un live coding pour voir le result | [live](#live)                       |
| showLineNumbers | afficher les numero de ligne             | [showLineNumbers](#showlinenumbers) |
| highlight       | mettre en evidence                       | [highlight](#highlight)             |
| Tabulation      | pour faire plusieurs language            | [tab](#tabulation)                  |

### Live

```ts live

function toto(): number {
    return 1
}

```

### ShowLineNumbers

```ts showLineNumbers

function toto(): number {
    return 1
}

```

### Highlight

1. Premier facon

``` ts

// highlight-start
function toto(): number {
// highlight-end
    return 1
}

```

2. Deuxieme Facon

``` ts {1,2-2,4}

function toto(): number {

    console.log("hello")

    return 1
}

```

### Tabulation

````md
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
<TabItem value="js" label="JavaScript">

```js
function helloWorld() {
  console.log('Hello, world!');
}
```

</TabItem>
<TabItem value="py" label="Python">

```py
def hello_world():
  print("Hello, world!")
```

</TabItem>
<TabItem value="java" label="Java">

```java
class HelloWorld {
  public static void main(String args[]) {
    System.out.println("Hello, World");
  }
}
```

</TabItem>
</Tabs>
````

le **Resultat**:

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
<TabItem value="js" label="JavaScript">

```js
function helloWorld() {
  console.log('Hello, world!');
}
```

</TabItem>
<TabItem value="py" label="Python">

```py
def hello_world():
  print("Hello, world!")
```

</TabItem>
<TabItem value="java" label="Java">

```java
class HelloWorld {
  public static void main(String args[]) {
    System.out.println("Hello, World");
  }
}
```

</TabItem>
</Tabs>

## Language de programmation accepter

| Nom              | code    |
|------------------|---------|
| javascript       | js      |
| typescript       | ts      |
| kotlin           | kotlin  |
| golang           | go      |
| python           | python  |
| javascript react | jsx     |
| typescript react | tsx     |
| rust             | rust    |
| graphql          | graphql |
| yaml             | yaml    |
| cpp              | cpp     |
| json             | json    |
