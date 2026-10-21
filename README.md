# Propostas de site · Rolândia-PR

21 protótipos de landing page (uma página, mobile-first, HTML + CSS estático) para negócios de Rolândia-PR, com identidade visual própria para cada um. Proposta de Matheus Vinicius.

## Estrutura

```
index.html            lista de todos os protótipos, por segmento
sites/<slug>.html     um arquivo por negócio (CSS embutido, sem dependências)
robots.txt            bloqueia indexação (são protótipos)
```

Cada página tem: faixa "Protótipo · proposta de Matheus Vinicius", hero com CTA, cardápio/serviços, galeria (placeholders), horário e contato. Celulares (9 dígitos) ganham botão `wa.me`; telefones fixos ganham botão de ligar.

## Campos a preencher

Preços, horários, endereço, Instagram e fotos não foram inventados: aparecem como campos tracejados "a preencher". No HTML, procure por `class="fill"` e troque pelo conteúdo real. Os itens de cardápio/serviço são ilustrativos e estão sinalizados como tal na página.

## Publicar no Netlify

Arraste a pasta do projeto em app.netlify.com/drop, ou conecte o repositório com publish directory `.` e sem comando de build.
