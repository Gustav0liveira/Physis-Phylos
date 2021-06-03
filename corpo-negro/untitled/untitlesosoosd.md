---
description: >-
  Já existia no começo do século XIX, um entendimento geral a respeito do
  mecanismo por trás do processos de emissão de luz e radiação infravermelho em
  corpos quando aquecidos.
---

# Radiação de Corpos Aquecidos

Todos os corpos com uma temperatura $$T$$ acima do zero absoluto devem apresentar energia associada a graus de liberdades internos, geralmente na forma do movimento desordenado de vibração dos seus átomos e moléculas. 

Um resultado do eletromagnetismo clássico conhecido da época, entretanto, é a de que cargas elétricas aceleradas devem emitir ondas eletromagnéticas \(radiação\). Assim, como átomos não são mais do que padrões complicados de cargas elétricas mais elementares, a esse movimentos de vibração molecular deve estar associado a emissão de radiação eletromagnética, como a radiação infravermelho emitida pela a maior parte dos objetos a temperatura ambiente e como a de luz por parte de um objeto aquecido.



## Lei de Stefan-Boltzmann

A primeira conjectura quantitativa sobre os corpos negros foi feita em  1879 por _Joseph Stefan_, na forma

$$
j(T) = \sigma T^4
$$

onde $$\sigma=5{,}67\times10^{-8}\frac{W}{m^2K^4}$$ e $$j(T)$$ é a potencia radiada por metro quadrada a uma dada temperatura $$T$$.

Tal expressão foi mais tarde deduzida por _Ludwig Boltzmann_ através de considerações termodinâmicas da radiação eletromagnética contida num caixa fechada com parede reflexivas. 

Imaginando um série de ondas planas monocromáticas contidas no interior do recipientes, é possível mostrar que a densidade de energia eletromagnética $$u$$ e a densidade de momento eletromagnético $$p_v$$ estão relacionados por meio da forma $$u=cp_v$$. Logo

$$
dp=p_vdV=p_vdldA=p_v(cdt)dA
$$

Mas como, $$dF=\frac{dp_v}{dt}=cp_vdA=udA.$$ Temos que a pressão exercida pela radiação nas paredes deve ser dada por

$$
P=\frac{dF}{dA}=u
$$

Mas como espera-se que que a pressão seja a mesma que em todas as três direções independentes, temos que $$P=\frac{1}{3}u$$. Usando a relação fundamental da termodinâmica $$dU=TdS=PdV$$ a uma variação isotérmica do volume

$$
\left(\dfrac{\partial U}{\partial V}\right)_T=T\left(\dfrac{\partial S}{\partial V}\right)_T-P
$$

Assim, usando a relação de Maxwell $$\left(\frac{\partial S}{\partial V}\right)_T=\left(\frac{\partial P}{\partial T}\right)_V$$ e $$U=Vu(T)$$, temos que

$$
\dfrac{\partial }{\partial V}\left[Vu(T)\right]_T=T\left(\dfrac{\partial P}{\partial T}\right)_V-P
$$

Assim

$$
u=T\left(\dfrac{\partial P}{\partial T}\right)_V-P
$$

Para $$P=\frac{u}{3}$$ e $$dP=\frac{du}{3}$$, temos que:

$$
\frac{4}{3}u=\frac{T}{3}\frac{du}{dT}\implies4\frac{dT}{T}=\frac{du}{u}du
$$

Que integrando da origem á

$$
u(T)=\sigma T^4
$$

Que é a expressão para a lei de Stefan-Boltzmann.

