# Método N7D™ - Negócio Digital em 7 Dias

Uma landing page dinâmica de venda + e-book completo para ensinar iniciantes a criar um negócio digital em Angola.

## 📁 Estrutura do Projeto

```
negocio-digital-7-dias/
├── index.html              # Landing page responsiva
├── README.md              # Este arquivo
├── content/
│   ├── ebook.md           # E-book completo (11 capítulos)
│   └── prompts.md         # 50+ prompts de IA prontos
└── assets/                # (Para adicionar: imagens, fontes, etc)
```

## 🚀 Como Usar

### Landing Page

1. Abra `index.html` no navegador
2. A página é responsiva (funciona em celular, tablet e desktop)
3. Customize cores, textos e links conforme necessário

**Elementos principales da landing:**
- Hero Section com proposta de valor
- O que você vai receber
- Preço e garantia
- Testimonios
- CTA (Call-to-Action) para checkout

### E-book

O e-book completo está em `content/ebook.md` com:
- 11 capítulos estruturados
- 1 introdução + 1 conclusão
- Exercícios para cada capítulo
- Checklists de implementação
- Casos práticos reais
- Estrutura totalmente profissional

**Pode ser usado como:**
- Markdown file (para ler direto)
- Exportado para PDF (File → Print → Save as PDF)
- Convertido para EPUB (usando Pandoc)
- Material de aula/workshop

## 🎨 Customizando a Landing Page

### Cores

As cores principais são:
- Azul escuro: `#1a1a2e`, `#16213e`, `#0f3460`
- Amarelo: `#ffc107`
- Cyan: `#00d4ff`

Mude no CSS (seção `:root` ou inline styles)

### Textos

Todos os textos são edináveis diretamente no HTML. Procure por:
- `<h1>` - Título principal
- `<p>` - Parágrafos
- `.section-title` - Títulos de seções
- `.cta-primary` - Botões

### Imagem Hero

Encontre a seção `.hero-image` e substitua:

```html
<!-- De: -->
<div class="placeholder-image">
    🚀 Sua Imagem Aqui
</div>

<!-- Para: -->
<img src="seu-arquivo.jpg" alt="Descrição">
```

## 💰 Implementar Pagamentos

A landing page tem estrutura pronta para integração de pagamentos:

### Opção 1: Paga Tudo Angola

```html
<a href="https://pagatudo.ao/checkout/[seu-link]" class="cta-primary">
    GARANTIR ACESSO AGORA
</a>
```

### Opção 2: PayPal

```html
<form action="https://www.paypal.com/cgi-bin/webscr" method="post">
    <input type="hidden" name="cmd" value="_xclick">
    <input type="hidden" name="business" value="seu-email@paypal.com">
    <button type="submit" class="cta-primary">GARANTIR ACESSO AGORA</button>
</form>
```

### Opção 3: Stripe

Integre Stripe.js para processamento seguro de cartões.

## 📊 Estrutura do E-book

### 11 Capítulos

1. **Introdução** - Contexto e promessas
2. **A Nova Economia Digital** - Entendendo o mercado
3. **Como Escolher um Negócio Digital** - 7 tipos + recomendação
4. **Como Criar Uma Oferta Irresistível** - Estrutura de oferta
5. **Como Utilizar IA Para Trabalhar Mais** - ChatGPT, Gemini, Midjourney
6. **Como Criar Presença Profissional Online** - WhatsApp, Google Business, Portfólio
7. **Como Conseguir Primeiros Clientes** - 3 canais de prospecção
8. **Como Fazer Primeiras Vendas** - 5 estágios de venda
9. **Como Escalar Para 100.000+ Kz** - Delegação e automação
10. **Como Escalar Para 100.000+ Kz (Continuação)** - Consolidação
11. **Plano de Ação 30 Dias** - Semana a semana
12. **Conclusão** - Próximos passos

### Por Capítulo

- Explicação profunda (1.500-2.000 palavras)
- 2-3 casos práticos reais
- Passo a passo detalhado
- Erros comuns e soluções
- 1 exercício de implementação
- 1 checklist final

## 🤖 50+ Prompts de IA

Arquivo `content/prompts.md` com prompts prontos para:
- Copywriting
- Criação de conteúdo
- Email e mensagens
- Pesquisa
- Produtos digitais
- Brainstorm

**Como usar:**
1. Abra o arquivo
2. Copie o prompt que quiser
3. Cole no ChatGPT/Gemini
4. Customize conforme necessário

## 📈 Métricas de Conversão

Para medir efetividade da landing page:

- **Visitantes totais**
- **Taxa de clique no CTA** (ideal: 3-5%)
- **Leads capturados** (se usar form)
- **Conversão para venda** (ideal: 1-3%)
- **Ticket médio**

Integre Google Analytics para rastrear.

## 🔧 Otimizações Recomendadas

### Imediatas
- [ ] Adicionar imagem profissional na hero
- [ ] Customizar cores da marca
- [ ] Integrar método de pagamento real
- [ ] Adicionar seus depoimentos reais

### Curto Prazo (1-2 semanas)
- [ ] Criar versão em PDF do e-book
- [ ] Setup Google Analytics
- [ ] Otimizar SEO (title, meta descriptions)
- [ ] Criar email de follow-up automático

### Médio Prazo (1 mês)
- [ ] Testar diferentes CTAs
- [ ] A/B test de preços
- [ ] Criar landing pages para diferentes públicos
- [ ] Implementar live chat

## 📱 Mobile Optimization

A landing page já é responsiva, mas teste em:
- iPhone (375px)
- Android (360px)
- iPad (768px)
- Desktop (1200px)

## 🔒 Segurança

Se implementar pagamentos:
- Use HTTPS sempre
- Não armazene dados sensíveis
- Use tokens de segurança
- Cumpla com GDPR/regulações

## 📞 Próximos Passos

1. **Setup landing page:**
   - Personalizar
   - Integrar pagamento
   - Publicar online

2. **Distribuição do e-book:**
   - Converter para PDF
   - Enviar após compra automáticamente
   - Criar versão impressa (opcional)

3. **Marketing:**
   - Facebook Ads
   - Google Ads
   - Grupos Facebook
   - Influencers locais
   - Email marketing

## 📄 Licença

Esse material é criado para uso comercial. Personalize livremente.

## 🤝 Suporte

Para customizações avançadas, revise:
- `index.html` - Estrutura HTML
- CSS sections - Estilos customizados
- JavaScript - Funcionalidades interativas

---

**Criado com dedicação para empreendedores angolanos.**

**Método N7D™ - Transforme seu tempo em dinheiro em 7 dias.**
