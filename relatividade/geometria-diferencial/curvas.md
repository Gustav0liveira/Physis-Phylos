# Curvas

Curvas são objetos unidimensionais cujas características independem de onde estão inseridas, entretanto, para a nossa descrição será interessante começarmos com uma abordagem extrínseca onde uma curva pode ser imaginada como um traço imerso num ambiente tridimensional. A forma mais econômica de caracteriza-las preservando as técnicas do cálculo diferencial passa pela introdução do conceito de uma _curva diferencial parametrizada_

$$
\bm{r}(t)=\left(x(t),y(t),z(t)\right)
$$

onde $$\bm{r}$$ - chamado de vetor posição - é uma aplicação que mapeia todos os valores de um parâmetro $$t$$ pertencente a um conjunto aberto $$I\subset \mathbb{R}$$ até cada terna $$(x,y,z)$$ de pontos do $$\mathbb{R}^3$$.

A primeira propriedade geométrica de interesse de uma curva é a sua extensão ao longo do espaço que é caracterizada pelo seu comprimento de arco $$s$$. Dados dois pontos arbitrários pertencentes a curva $$P: \bm{r}(t)$$ e $$Q:\bm{r}(t+\Delta t)$$ é possível definir o vetor diferença $$\Delta \bm{r}=\bm{r}(t+\Delta t)-\bm{r}(t)$$ que determina a corda PQ que intersecta a curva nos pontos e cujo o módulo

$$
\| \Delta \bm{r}\| \simeq \Delta s
$$

se aproxima do comprimento de arco da curva para pequenos valores de $$\Delta t$$. Tomando o limite em que $$\Delta t\to0$$ é possível identificar o elemento infinitesimal de comprimento de arco $$ds$$ como

$$
ds=\lim_{\Delta t \to 0}\left|\frac{\bm{r}(t+\Delta t)-\bm{r}(t)}{\Delta t}\right|\Delta t=\left|\frac{d \bm{r}}{dt}\right| dt
$$

onde conforme os pontos se aproximam infinitesimalmente um do outro, o vetor $$\Delta r$$ começa a apontar na direção tangente a curva enquanto o fator $$1/\Delta t$$ corrige o seu tamanho, garantindo a convergência para uma magnitude finita $$\text{v}=\left|\frac{d \bm{r}}{dt}\right|$$ dada pelo módulo do vetor velocidade $$\bm{v}$$.

A partir da expressão é possível então encontrar a função comprimento de arco $$s(t)$$ que mede o comprimento da curva do ponto $$t_0$$ até $$t$$ e é dado por

$$
s(t)=\int_{t_0}^{t}ds=\int_{t_0}^{t}\left\|\frac{d\bm{r}}{dt}\right\|dt=\int_{t_0}^{t}\sqrt{\frac{d\bm{r}}{dt}\cdot\frac{d\bm{r}}{dt}}dt.
$$

{% hint style="info" %}
Uma _curva parametrizada regular_ é uma aplicação de $$\mathbf{r}:U\subset \mathbb{R}\to\mathbb{R}^3$$que conecta os elementos de um conjunto aberto $$I\subset\mathbb{R}$$ até a terna $$(x,y,z)\in\mathbb{R}^3$$ de tal forma que&#x20;

* $$\mathbf{r}$$ é diferenciável de classe $$C^{\infty}$$&#x20;
* O vetor velocidade seja não nulo es $$\mathbf{r}^{\prime}(t)$$ seja não nulo para todo $$t$$.&#x20;
{% endhint %}

&#x20;

&#x20;

&#x20;
