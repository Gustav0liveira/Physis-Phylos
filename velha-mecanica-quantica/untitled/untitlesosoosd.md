---
description: Porque objetos quando aquecidos emitem luz de diferentes cores?
---

# Radiação de Corpos Aquecidos

## Introdução

Já existia no começo do século XIX, um entendimento geral a respeito dos mecanismos por trás do processos de emissão de luz e radiação infravermelha em corpos quando aquecidos.

A temperatura de um objeto é uma medida do seu grau de agitação molecular, de forma que aquecer um corpo transferindo energia na forma de calor, significa aumentar a energia por grau de liberdade interno, incrementando o movimento desordenado de agitação dos seus constituintes microscópicos.

Dessa forma, um corpo a uma temperatura $$T$$ acima do zero absoluto, devido ao movimento desordenado de seus átomos \(que nada mais são que padrões complicados de cargas elétricas mais elementares\), deve induzir a oscilação de cargas elétricas, e consequentemente, como prevê o eletromagnetismo clássico, a emissão de radiação eletromagnética.

## 

Existem basicamente três processos 





## Lei de Stefan-Boltzmann

A primeira conjectura quantitativa sobre os corpos negros foi feita em  1879 por _Joseph Stefan_, na forma

$$
u(T) = \sigma T^4
$$

onde $$\sigma=5{,}67\times10^{-8}\frac{W}{m^2K^4}$$ e $$j(T)$$ é a potencia radiada por metro quadrado a uma dada temperatura $$T$$.

Tal expressão foi mais tarde deduzida por _Ludwig Boltzmann_ através de considerações termodinâmicas da radiação eletromagnética contida num caixa fechada com paredes reflexivas. 

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
\frac{4}{3}u=\frac{T}{3}\frac{du}{dT}\implies4\frac{dT}{T}=\frac{du}{u}
$$

Que integrando, da origem á

$$
u(T)=\sigma T^4
$$

Que é a expressão para a lei de Stefan-Boltzmann.

## Lei de Rayleigh-Jeans

### Radiação como Ondas Estacionárias

Tratando a radiação de corpo negro como um campo eletromagnético confinado numa cavidade cúbica \(lados $$L$$\) de paredes metálicas \(reflexivas\), é possível mostrar \([ver apêndice](apendices.md#onda-eletromagnetica-numa-cavidade)\) que a radiação deve consistir em ondas estacionárias com um espectro discreto para os possíveis valores de frequência 

$$
\begin{matrix} \nu^2=\left(\frac{c}{2L}\right)^2\left(l^2+m^2+n^2\right)=\left(\frac{c}{2L}\right)^2p^2 & &\text{com} &l,m,n=1,2,... \end{matrix}
$$

Logo, encontremos o número de modos normais de oscilação contando o número de pontos no espaço de $$p$$ num intervalo de frequências de $$\nu$$á $$\nu+d\nu$$na forma

$$
dN=\eta(p)dp=\left(\frac{1}{8}\right)4\pi p^2dp
$$

para $$\nu=\frac{c p}{2L} \implies d\nu=\frac{c}{2L}dp$$, temos que $$p^2dp=\left(\frac{2L\nu}{c}\right)^2\left(\frac{2L}{c}\nu\right)=\left(\frac{2L}{c}\right)^3\nu^2d\nu$$ e, portanto, $$dN=\frac{4\pi\nu^2}{c^3}Vd\nu.$$ Considerando além disso a existência de duas possíveis direções de polarização e $$L^3=V$$ , concluímos a contagem com

$$
dN=\dfrac{8\pi\nu^2}{c^3}Vd\nu
$$

Logo, a densidade volumétrica do número de modos de oscilação deve ser dada por $$d\eta=\dfrac{8\pi\nu^2}{c^3}d\nu$$.

