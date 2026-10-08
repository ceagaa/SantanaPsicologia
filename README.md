# Santana Psicologia

Site institucional da clínica do **Thiago Santana**, psicólogo (CRP 06/140539), em Mogi das Cruzes/SP.
O objetivo é simples: apresentar o trabalho, passar confiança e facilitar o primeiro contato pelo WhatsApp.

---

## O que tem por aqui

- **`index.html`** – a home: apresentação, sobre mim, serviços, depoimentos, dúvidas frequentes e contato.
- **`politica-de-privacidade.html`** – a política de privacidade (LGPD), linkada lá no rodapé.
- HTML + CSS + um pouquinho de JavaScript. Sem build, sem framework, sem `npm install`.

## Como abrir

O jeito mais fácil é dar dois cliques no `index.html`. Se preferir ver como um site de verdade (evita uns bloqueios do navegador com imagens e scripts locais), sobe um servidor estático qualquer:

```bash
# com Node.js
npx serve .

# ou com Python
python -m http.server 8080
```

Depois é só abrir `http://localhost:8080`.

## Estrutura

```
SantanaPsicologia/
├── index.html                       # home
├── politica-de-privacidade.html     # política de privacidade
├── css/                             # style guide e variáveis de cor
├── js/                              # jQuery + scripts do Webflow (interações)
├── fonts/                           # fontes do site
└── img/
    ├── logo/                        # logo branco e favicon
    ├── hero/                        # imagem de destaque do topo
    ├── sobre/                       # foto da seção "Sobre mim"
    └── placeholder-depoimento-*.svg # imagens dos depoimentos
```

## O que costuma ser editado

- **Textos** – direto no HTML. A home está toda em `index.html`, organizada por seção (`#about`, `#services`, `#testimonial`, `#portfolio`, `#contact`).
- **Cores** – variáveis no início de `css/handymanpro-template.webflow.shared.a7c15f822.css`. O teal `#017e7b` e o verde dos botões `#c8f461` são as cores da marca.
- **Imagens** – é só substituir o arquivo dentro de `img/` mantendo o mesmo nome.
- **WhatsApp** – o botão da seção de contato aponta para `https://wa.me/5511949300712`; é ali que se troca o número.

## Observações

- O site foi exportado do Webflow, então o HTML vem "compacto" (tudo em poucas linhas). Edite com cuidado e mantenha a codificação em **UTF-8**.
- Não há cookies de rastreamento, como descrito na política de privacidade.
- Redes sociais estão com links `#` de propósito: só preencher quando houver os perfis reais.

---

Desenvolvido por **2swebtech**.
