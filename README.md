# Escena principal de Unity

## Descrición xeral

Nesta escena de Unity represéntase un pequeno xogo, o escenario inclúe tres personaxes con comportamentos diferentes que interactúan entre si.

## Personaxes

### Bruxa (personaxe xogable)
A **bruxa** é o personaxe controlado polo xogador.  
Pódese mover polo escenario empregando o *teclado* (frechas ou teclas WASD), permitindo desprazamentos en todas as direccións.

- Controlada polo xogador  
- Movemento fluído co teclado  
- Personaxe principal da escena  

### Pantasma
O **pantasma** é un personaxe inimigo que persegue constantemente á bruxa polo escenario.

- Movemento automático  
- Velocidade **rápida**  
- Sempre tenta achegarse á bruxa  

### Zombie
O **zombie** é outro personaxe inimigo que segue ao pantasma.

- Movemento automático  
- Velocidade **máis lenta** ca do pantasma  
- Persegue ao pantasma polo escenario  

## Dinámica da escena

A escena xera unha cadea de persecución:

- A bruxa tenta escapar usando o teclado  
- O pantasma persegue á bruxa rapidamente  
- O zombie segue ao pantasma a menor velocidade  