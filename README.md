# Imersivo 3D — Site institucional

Site institucional bilíngue (PT-BR / EN) da **Imersivo 3D** — imóveis, projetos e ambientes transformados em experiências digitais navegáveis (modelagem 3D, Realidade Aumentada e Realidade Virtual).

**Ao vivo:** https://imersivo-3d.vercel.app

## Destaques
- Hero cinemático com cena 3D (Three.js) de um apartamento "digitalizado".
- Walkthrough 3D fixo: a câmera percorre os ambientes conforme o scroll (Entrada → Sala → Cozinha → Suíte).
- Galeria de renders com parallax, comparador planta 2D → ambiente 3D, e visor VR (POV).
- Seção de Planos (Tour 360° a partir de R$ 990) e demo 360° incorporado.
- Scroll suave (Lenis), seletor de idioma PT/EN, responsivo e com fallback de baixa performance.

## Stack
HTML/CSS/JS estático · Three.js (r128) · Lenis · Google Fonts. Sem build — deploy estático na Vercel.

## Desenvolvimento
Abra `index.html` em qualquer navegador. Qualquer push para `master` dispara deploy automático na Vercel.
