# Cálculo de Monte Carlo para o modelo de Ising

*Este código foi escrito para a simulação do modelo de Ising pedido 
pelo Professor Silvio Salinas na matéria de Mecânica Estatística
oferecida no segundo semestre de 2022 no Instituto de Física - USP.*

**Simulação de Monte Carlo para o modelo de Ising 2D**

"O algoritmo de Metropolis estabelece uma prescrição para gerar uma cadeia
de configurações microscópicas que devem convergir para as configurações 
representativas do estado gibbsiano de equilíbrio.

A implementação do algoritmo de Metropolis, para uma rede $N \times N$, a uma
dada temperatura $T$, pode ser feita de acordo com as seguintes etapas:

(i) escolhe-se uma configuração de spins da rede (nesse código foi escolhido
todos os spins para cima). Seleciona-se um sítio qualquer da rede;

(ii) selecionado o sítio da rede, muda-se o valor do spin. A configuração
microscópica inicial, com energia $E_{i}$, transforma-se numa configuração final,
com energia $E_{f}$. É calculado $r = \exp{(- \Delta E / T)}$, em que 
$\Delta E = E_{f} - E_{i}$;

(iii) se $\Delta E < 0$, a nova configuração microscópica é aceita, e é dado
continuidade ao processo, selecionando outro sítio da rede;

(iv) se $\Delta E > 0$, é comparado o valor de $r$ com um número aleatório
$z$ entre $0$ e $1$. Aceta-se a mudança de sinal do spin escolhido se $r > z$,
mantém-se o mesmo sinal se $r < z$"

Referência:

https://rajeshrinet.github.io/blog/2014/ising-model/

*falta escrever instruções de como usar*
