# Programação?

---

## O que é:

São algorítimos que por sua vez são passos lógicos para executar uma determinada tarefa. Ex:

 ** Algorítimo de lavar a roupa: **
 
 1. Coletar roupas sujas
 2. Armazenar roupas sujas
 3. Levar as roupas armazenasdas até a lavanderia
 4. Encher a máquina de lavar roupa de água
 5. Colocar sabão na máquina
 6. Inserir amaciante 
 7. Colocar a roupa na máquina
 8. Iniciar a função de lavagem da máquina
 9. Aguardar o fim da execução da lavagem da roupa na máquina

---

## Como o computador entende?

Para começar, é bom enfatizar em conceito:

> O compudador não pensa, apenas processa e calcula bem mais rápido do que nós, humanos

> O computador apenas recebe órdens atravéz das linguagens de programação

A partir dessas afirmações é possível entender que para que o computador execute um algorítimo, é preciso se comunicar com o computador atravéz das linguagens de programação de forma a indicar a sequência lógica de passos que o computador precisa executar para atingir um determinado objetivo.

--

## Dar instruções a um computador

Como foi falado durante todo esse artigo, programação é uma sequência de passos como mostrado abaixo:

 1. Armazenar roupas sujas
 2. Levar as roupas armazenasdas até a lavanderia
 3. Encher a máquina de lavar roupa de água
 4. Colocar sabão na máquina
 5. Inserir amaciante 
 6. Colocar a roupa na máquina
 7. Iniciar a função de lavagem da máquina
 8. Aguardar o fim da execução da lavagem da roupa na máquina


Esse algorítmo de como lavar a roupa parece perfeito, porém ele peca em uma parte: 


> - Não se sabe a quantidade de __roupa__ que é necessária para se executar essa tarefa
>
> - Não se sabe a quantidade de __sabão__ que é necessária para se executar essa tarefa
>
> - Não se sabe a quantidade de __amaciante__ que é necessária para se executar essa tarefa
>
> - Não se sabe a quantidade de __água__ que é necessária para se executar essa tarefa
>
> -  não existe uma etapa verificando cada um desses dados para se tomar uma decisão lógica como: se eu tiver uma quantidade X de roupas devo colocar Y de água Z de sabão e K de amaciante

Então como podemos ver, para que um algorítmo seja efetivo precisamos de dados, informações detalhadas sobre o que precisa ser feito para que uma determinada ação seja executada. Nosso algorítmo de lavar a roupa ficaria assim corrigindo esse erros:

 1. Armazenar __4kg__ roupas sujas
 2. Levar as roupas armazenasdas até a lavanderia
 3. Verificar a quantidade proporcional de insumos que precisam ser consumidos na lavagem com base no peso das roupas armazenadas
 4. Encher a máquina de lavar roupa com __30L de água__
 5. Colocar __150g__ de sabão na máquina
 6. Inserir __300ml__ de amaciante 
 7. Colocar a roupa na máquina
 8. Iniciar a função de lavagem da máquina
 9. Aguardar o fim da execução da lavagem da roupa na máquina