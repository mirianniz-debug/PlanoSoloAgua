Geoportal do Plano Municipal de Conservação do Solo e da Água no Meio Rural de Jaguariúna/SP (revisão 2026): nascentes e vulnerabilidade à erosão, sub-bacias prioritárias, áreas a recompor e a terracear, e ações já realizadas.

🔗 **Acesse ao vivo:** https://mirianniz-debug.github.io/PlanoSoloAgua/

Elaboração: Departamento de Agropecuária e Meio Ambiente (DAMA), Prefeitura Municipal de Jaguariúna. Os limites e as áreas são aproximados e têm finalidade de planejamento; as nascentes ainda não foram verificadas em campo.

## Visualizar localmente

O mapa carrega os dados de `data/` com `fetch`, então não abre com duplo clique no `index.html`: é preciso servir a pasta por um servidor local (qualquer servidor estático) e abrir `http://localhost:<porta>/`.

## Incorporando o geoportal em outro site (iframe)

O `index.html` é responsivo, mas isso só funciona se o `<iframe>` que o incorpora também for responsivo. Use sempre largura em porcentagem, nunca um valor fixo em pixels:

```html
<iframe src="URL_DO_GEOPORTAL" style="width:100%; border:0;" height="600" loading="lazy"></iframe>
```

## Licença

Todos os direitos reservados. Ver [LICENSE](LICENSE).
