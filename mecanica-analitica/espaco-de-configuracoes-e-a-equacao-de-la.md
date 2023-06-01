# Espaço de configurações e a equação de La

Na mecânica newtoniana, precisamos de 3 componentes do vetor posição para localizar uma partícula livre. O número de parâmetros independentes necessários para caracterizar a trajetória de todas as suas partículas é chamado de **grau de liberdade**. Para um sistema de $$N$$partículas livres, o número de graus de liberdades do sistema é portanto, de $$n=3N$$.

Caso tais partículas não estejam livres, o número de graus de liberdade diminui. Um exemplo é a de uma partícula presa por uma haste de tamanho fixo $$l$$ que pode oscilar sobre o plano $$y=0$$. Esse sistema possui duas equações cinemáticas que restringem as possíveis posições ocupadas pela partícula, sejam

$$
y=0\\ \sqrt{x^2+y^2}=l
$$

Dizemos assim que o sistema possui um número $$s=2$$ de vínculos e estes são responsáveis por fazer a partícula ficar restrita a oscilar numa circunferência de raio $$l$$, ou seja, ao longo de uma região unidimensional.

Não precisamos entretanto, nos restringir as coordenadas cartesianas. Definindo as coordenadas esféricas por meio das transformações

$$
x=r\cos \theta \sin \phi\\ y=r\sin\theta\sin \phi\\ z=r\cos\phi,
$$

nos permite expressar os vínculos como

$$
\theta=0\\ r=l.
$$

Estas últimas tornam óbvio o fato de que devido aos dois vínculos, o número de graus de liberdade do sistema foi reduzido a $$n=1$$, pois apenas especificando o valor do parâmetro $$\phi$$ podemos caracterizar completamente a trajetória da nossa partícula.

Para um sistema geral de $$N$$partículas com $$s$$ vínculos, o número de graus de liberdade é dado por

$$
n=3N-s.
$$

No exemplo anterior vimos que a descrição cinemática de um sistema mecânico não precisa ficar restrita avariáveis cartesianas, mas pode ser generalizada para quaisquer sistemas de coordenadas ou conjunto de parâmetros suficientes para a sua caracterização. Para um sistema com $$n$$ graus de liberdade, chamamos o conjunto de tais parâmetros de **coordenadas generalizadas**

$$
q_k=\{q_1,q_2,\dots,q_n\}.
$$

O espaço matemático gerado por tais coordenadas é então denominado de **espaço de configurações** do sistema físico em questão.

Consideremos um sistema de $$N$$ partículas sob a ação de uma força resultante $$\mathbf{F}$$. A segunda lei de Newton para este sistema lê-se

$$
\mathbf{F}_i(\mathbf{r},t)= m_i \frac{d\mathbf{v}_i(t)}{dt} \qquad i=1,\dots, N.
$$

Usando o fato que $$\frac{d}{dt}|\mathbf{v}|^2=2\mathbf{v}\cdot \frac{d \mathbf{v}}{dt}$$, multiplicando a última expressão&#x20;

