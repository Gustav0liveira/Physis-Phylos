---
description: Porque objetos quando aquecidos emitem luz de diferentes cores?
---

# Corpo Negro



## Lei de Stefan-Boltzmann

A primeira conjectura quantitativa sobre os corpos negros foi feita em  1879 por _Joseph Stefan_, na forma

$$
u(T) = \sigma T^4
$$

onde $$\sigma=5{,}67\times10^{-8}\frac{W}{m^2K^4}$$ e $$j(T)$$ é a potencia radiada por metro quadrado a uma dada temperatura $$T$$.

Tal expressão foi mais tarde deduzida por _Ludwig Boltzmann_ através de considerações termodinâmicas da radiação eletromagnética contida num caixa fechada com paredes reflexivas. 

Imaginando um série de ondas planas monocromáticas contidas no interior do recipientes, é possível mostrar que a densidade de energia eletromagnética $$u$$ e a densidade de momento eletromagnético $$p_v$$ estão relacionados por meio da relação $$u=cp_v$$\([ver apêndice](../apendices.md#densidades-de-energia-e-momento-eletromagnetico)\). Logo

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

## Lei do Deslocamento de Wien

Outra relação quantitativa a respeito da radiação de um corpo negro foi primeiramente proposta teoricamente por Wilhem Wien em 1893 e afima que

{% hint style="success" %}
O comprimento de onda máximo para curva da distribuição espectral da emissão de um corpo negro é inversamente proporcional a sua temperatura

$$\lambda_{max}=\dfrac{c}{T} \ \ \text{com} \ \ b=2{,}897\times10^{-3}mK$$ 
{% endhint %}

![Curva da densidade de energia espectral por comprimento de onda em diversas temperaturas.](../../../.gitbook/assets/wiens_law.svg)

A partir da [Lei de Stefan/Boltzmann ](./#lei-de-stefan-boltzmann)onde $$u(T)=\sigma T^4$$ e das considerações a respeito da pressão exercida pelo campo eletromagnético no seu interior da cavidade deduzida naquela discussão, dado por $$P=\frac{1}{3}u$$ , tem-se que

$$
3P=u(T)=\sigma T^4
$$

Para um variação isovolumétrica da temperatura \(e usando a relação de Maxwell $$\left(\frac{\partial P}{\partial T}\right)_V=\left(\frac{\partial S}{\partial V}\right)_T$$ \)

$$
3\left(\dfrac{\partial P}{\partial T}\right)_V=3\left(\dfrac{\partial S}{\partial V}\right)_T=4\sigma T^3
$$

Logo, deduz-se que $$dS=4\sigma T^2 VdT+\frac{4}{3}\sigma T^3dV$$ , de forma que, para um processo adiabático \( $$dS=0$$ \), obtém-se

$$
4\sigma T^2\left(VdT+\frac{1}{3}TdV\right)=0 \implies\frac{dT}{T}=-\frac{1}{3}\frac{dV}{V}
$$

Cuja a integração direta resulta numa quantidade

$$
T^3 V=a=cte
$$

Que é o que chamamos de uma invariante adiabática, uma quantidade que mantém-se inalterada ao longo do processo que assumimos ser adiabático.

Acontece, que da análise da radiação contida em uma cavidade, verifica-se que \([Apêndice](../apendices.md#onda-eletromagnetica-numa-cavidade) e [Análise da Lei de Rayleigh-Jeans](./#lei-de-rayleigh-jeans)\) 

$$
\left(\frac{2\nu L}{c}\right)^2=\left(l^2+m^2+n^2\right) \ \ \text{com}  \ \ l,m,n=1,2,3,...
$$

Elevando a expressão a potência $$\frac{3}{2} $$, tem-se que $$\frac{8}{c^3}\nu^3L^3=\frac{8}{c^3}\nu^3V=\left(l^2+m^2+n^2\right)^{\frac{3}{2}}=cte$$ , permitindo encontrar uma nova invariante adiabática tomando o diferencial em ambos os lado

$$
\frac{8}{c^3}d\left(\nu^3V\right)=\frac{8}{c^3}\left(3\nu^2Vd\nu+\nu^3dV\right)=\frac{8}{c^3}\nu^2\left(3Vd\nu+\nu dV\right)=0
$$

Que dá origem as diferenciais separáveis $$\dfrac{d\nu}{\nu}=-\dfrac{1}{3}\dfrac{dV}{V}$$ , que por integração direta, dá origem ao nosso segundo invariante adiabático do sistema

$$
\nu^3V=b=cte
$$

Assim, introduzindo o primeiro invariante adiabático no segundo

$$
b=\nu^3V=\nu^3\left(\frac{a}{T^3}\right)\implies \frac{\nu}{T}=\left(\frac{b}{a}\right)^{\frac{1}{3}}=c=cte
$$

Que é a Lei de Wien em termos

## Lei de Rayleigh-Jeans

### Contando os Modos Normais de Oscilação

Tratando a radiação de corpo negro como um campo eletromagnético confinado numa cavidade cúbica \(lados $$L$$\) de paredes metálicas \(reflexivas\), é possível mostrar \([ver apêndice](../apendices.md#onda-eletromagnetica-numa-cavidade)\) que a radiação deve consistir em ondas estacionárias com um espectro discreto para os possíveis valores de frequência 

$$
\nu^2=\left(\frac{c}{2L}\right)^2\left(l^2+m^2+n^2\right)=\left(\frac{c}{2L}\right)^2p^2
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

Como resultado do teorema da equipartição da energia, no qual, cada grau de liberdade interno do sistema, contribui com uma energia média $$\frac{1}{2}k_BT$$,

{% hint style="info" %}
A descrição estatística para a probabilidade de um sistema a uma temperatura constante $$T$$ ser encontrado com uma determinada energia $$E$$ é fornecida pela distribuição de Maxwell-Boltzmann

 $$\rho=\dfrac{e^{-\frac{E}{k_B T}}}{\int e^{-\frac{E}{k_B T}}dqdp}$$ 

Logo, para cada termo quadrático na expressão para energia do sistema, $$E=\alpha p^2$$ o valor médio da energia deve ser dado por

$$\left<E\right>=\int E\rho(E,T)dqdp=\dfrac{\int E e^{-\frac{E}{k_B T}}dqdp}{\int e^{-\frac{E}{k_B T}}dqdp}=\dfrac{\int \left(\alpha p^2\right) e^{-\frac{\alpha p^2}{k_B T}}dqdp}{\int e^{-\frac{\alpha p^2}{k_B T}}dqdp}=\frac{1}{2}k_BT$$

onde $$\int \left(\alpha p^2\right) e^{-\frac{\alpha p^2}{k_B T}}dqdp=\frac{1}{2}k_B T\int  e^{-\frac{\alpha p^2}{k_B T}}dqdp$$ 
{% endhint %}

 Como é possível mostrar, a energia por modo de oscilação para o campo eletromagnético enclausurado na cavidade toma a forma $$E=\frac{1}{2m}P^2+\frac{1}{2}kQ^2$$ \([ver apêndice](../apendices.md#energia-do-campo-eletromagnetico-em-uma-cavidade)\) toma a forma  que cada modo normal de oscilação do campo eletromagnético deve ter uma energia média

$$
\left<E\right>=\left<\frac{1}{2m}P^2\right>+\left<\frac{1}{2}kQ^2\right>=k_BT
$$

Assim, a densidade de energia por modo de oscilação da radiação para uma frequência entre $$\nu$$ para $$\nu+d\nu$$ deve ser dada por

$$
u(\nu,T)=\left<E\right>d\eta=\dfrac{8\pi\nu^2}{c^3}k_B Td\nu
$$

Que é o resultado clássico para a distribuição espectral da densidade de energia.

### A Catástrofe do Ultravioleta

