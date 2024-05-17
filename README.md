trabalho-2
**estimativa de máxima verossimilhança**
 Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo espacial linear t-Student é dado por 

 $L (\theta) = log (K_{n}(\eta)) - \frac{1}{2} log (|\Sigma|) - 1/(2\eta) (1 + n\eta) log(1 + c(\eta) \delta),$

 
 **com** $log (K_{n} (\eta)) = \frac{\eta}{2} log (\frac{c(\eta)}{\pi}) + log \Gamma (\frac{1+\eta\eta}{2\eta}) - log \Gamma (\frac{1}{2\eta}) , \delta = \boldsymbol {(Y - X \beta)}^(T)\Sigma^{-1} \boldsymbol {(Y - X\beta )e} c(\eta) = (\eta)/(1 - 2\eta), 0 < (\eta) < \frac{1}{2}.$ Conforme observado por Zellner (1976), a função log-verossimilhança (4.4) é uma função decrescente de $(\eta)$ , e então não pode ser estimado por máximo verossimilhança. Veja também De Bastiani et al. (2015).
  As funções escores para o modelo espacial linear t-Student são fornecidas por  $U_{\theta}({\Theta}) = (U_{\beta}^{T} , U_{\phi}^{T})^{T}$, em que
 
 $U_{\beta} = {\partial}{L}({\Theta})/{\partial}{\beta} = w({\delta}) \boldsymbol{X}^T{\Sigma}^{-1}\epsilon$   and    $U_{\phi} = {\partial}{L}({\theta})/{\partial} {\phi},$
 
