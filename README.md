# Dr. Emmanuel Morais — Landing page

Site responsivo feito com HTML, CSS e JavaScript, sem dependências de build. Inclui efeitos de scroll, seção anatômica com profundidade/interação (simulação 2.5D baseada na arte original), carrossel acessível, modal de posts, FAQ, menu mobile e contatos.

## Abrir

Para pré-visualizar, execute na pasta do projeto:

```bash
python -m http.server 8080
```

Abra `http://localhost:8080` no navegador. Também é possível hospedar os arquivos em Vercel (projeto estático), Netlify ou qualquer hospedagem HTML.

## Conteúdo

As cinco fotos e artes originais estão em `assets/`. Os links de cada post e o WhatsApp podem ser configurados no editor opcional `admin.html`. O editor usa **localStorage**: as alterações ficam apenas no navegador/dispositivo em que são feitas, não são publicadas para outros visitantes e não constituem um CMS multiusuário. Para produção com edição sincronizada, é necessário conectar backend/autenticação e armazenamento (por exemplo Supabase).

## Pendências para publicação

- Confirmar e adicionar o telefone/WhatsApp oficial.
- Vincular URLs específicas de cada post, caso desejado.
- Verificar/autorizar direitos de uso das imagens fornecidas.
- Conferir textos e informações profissionais antes da publicação.
- Implementar backend seguro se desejar um painel admin real.

## WhatsApp configurado
Número: +55 84 92187-3474. A mensagem pré-preenchida é: "Olá, Dr. Emmanuel! Vim pelo seu site e gostaria de saber mais sobre os atendimentos e agendar uma avaliação.". O botão de contato e o botão flutuante abrem o WhatsApp diretamente.
