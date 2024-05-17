# rascunho


Para estimar os parâmetros do modelo,  adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo espacial linear t-Student é dado por 

$L(\theta) = log(K_{n}(\eta)) K n ( eta)) - \frac{1}{2}log|\Sigma| - \frac {1}{2} (\eta) (1 + n\eta) log(1 + c(\eta) \delta) $

com $log(k_{n}(\eta)) = frac {\eta}{2}log(\frac {c\eta)}{\pi})+log\Gamma (\frac{1-n\eta}{2\eta})-log \Gamma (\frac{1}{2\eta}) , \delta = (Y - X \beta)^{}\Sigma^-¹(Y-X\beta)$ é $c(\eta) = (\eta)/1-2(\eta)$, $0<\eta< \frac{1}{2}$. Conforme observado por Zellner (1976), a função log-verossimilhança é uma função decrescente de $(\eta)$, e então não pode ser estimado por máximo verossimilhança. Veja também De Bastiani et al. (2015).

As funções escores para o modelo espacial linear t-Student são fornecidos por $U_{\theta}(\theta)=(U^T_\beta,(U^T_\phi)$ em que 
 $U_(\beta)=\partial L (\theta) / \partial \beta = w(\delta) X^T \Sigma^-¹\epsilon$ e $U_\theta= \partial L (\theta)/\partial _\theta$,

 com o j-ésimo elemento de $U_\theta$, dado por $U_\theta {_j} = \partial L (\theta)/\partial _\theta {_j} = - \frac {1}{2} tr (\Sigma ^-¹(\partial \Sigma/ \partial _\theta {_j})) + \frac{1}{2}w(\beta)\epsilon ^T \Sigma ^-¹(\partial \Sigma/ \partial _\theta {_j}) \Sigma ^-¹\epsilon$ para $j=1,2, w(\beta) = ( \frac {1+ \eta n}{ \eta }) ( \frac {c(\eta)}{1+c(\eta)\beta})$ e $\psi(x)$ é a função Digama. Nesse artigo, $\Sigma = _\theta{_1} I _n + _\theta {_2} R$, então $\partial \Sigma/\partial _\theta {_1} = I_n$ e $\partial \Sigma/ \partial _\theta{_2} =R$. Dado $\Sigma$, a função log-verossimilhança é maximizada em 

 $\hat{\beta} = (X^T\Sigma^-¹X)^-¹X^T\Sigma^-¹Y$, 

 e de $U_\theta =0$ tem-se que,

 i) $_\theta{_1} tr(\Sigma^-¹\Sigma ^-¹) + _\theta {_1} tr(\Sigma^-¹ R \Sigma ^-¹) = w(\delta) \epsilon^T\Sigma ^-¹\Sigma ^-¹ \epsilon$,
 
 ii) ${_theta} tr(\Sigma^-¹R\Sigma ^-¹) + _\theta {_1} tr(\Sigma^-¹ R \Sigma ^-¹R) = w(\delta) \epsilon^T\Sigma ^-¹R\Sigma ^-¹ \epsilon$
