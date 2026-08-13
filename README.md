### Padrões modernos de JavaScript recomendam evitar var para minimizar bugs não intencionais.

<a href="https://github.com/user-attachments/assets/791c7a88-8709-4120-bb2d-12faab3545b2" >
  <img width="100%" alt="html-javascript" src="https://github.com/user-attachments/assets/791c7a88-8709-4120-bb2d-12faab3545b2"/>
</a>

&nbsp;

| Característica | var | let | const |
| --- | --- | --- | --- |
| Escopo | Função ou escopo global | Escopo de bloco { } | Escopo de bloco { } |
| Reatribuição | Pode ser atualizado | Pode ser atualizado | Não pode ser atualizado |
| Redeclaração | Pode ser redeclarado | Não pode ser redeclarado | Não pode ser redeclarado |
| Içamento | Inicializado como indefinido | Içado, não inicializado | Içado, não inicializado |

&nbsp;

<a href="https://github.com/user-attachments/assets/556efb65-119d-4a48-8058-c3e9be1f6e50" >
  <img width="100%" alt="var" src="https://github.com/user-attachments/assets/556efb65-119d-4a48-8058-c3e9be1f6e50" />
</a>

&nbsp;

> ⚠️ Atenção:
> A partir do ES6 (2015), é recomendado usar let e const no lugar de var, pois elas respeitam escopo de bloco e evitam comportamentos confusos:
