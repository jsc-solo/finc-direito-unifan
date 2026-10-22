# FINC | Stand de Direito UNIFAN · Que Crime Tenho Chance de Cometer?

Aplicação web interativa desenvolvida para o **Stand do Curso de Direito da UNIFAN (Centro Universitário Nobre)** durante o **FINC (Festival Internacional do Conhecimento)**, cujo tema oficial é **"A Era da IA: A Jornada da Inteligência Humana"**.

🔗 **Site Oficial do Festival:** [festivalfinc.com.br](https://festivalfinc.com.br/)

---

## ⚖️ Proposta do Experimento

O jogo simula um algoritmo de Inteligência Artificial que analisa a selfie do visitante para gerar uma **"Ficha de Suspeito"** fictícia e cômica (ex.: *Roubo de Batatas Fritas*, *Fraude no UNO*, etc.). 

Ao final, a aplicação desconstrói a brincadeira e conduz o participante a uma **reflexão ética e jurídica**:
* **Presunção de Inocência:** Como garantido pelo Art. 5º, LVII da Constituição Federal de 1988 (*"Ninguém será considerado culpado até o trânsito em julgado de sentença penal condenatória"*).
* **Superação do Lombrosianismo:** As teorias do século XIX que tentavam associar anatomia facial ao crime são pseudociências perigosas.
* **Perigos do Viés Algorítmico:** O reconhecimento facial automatizado sem supervisão jurídica e ética gera riscos de estigmatização e prisões injustas de inocentes.

---

## 🚀 Funcionalidades

* **Captura Instantânea de Selfie:** Integração nativa com a webcam/câmera frontal via `getUserMedia` com espelhamento e guia facial.
* **Fallback para Upload:** Suporte para escolher fotos direto da galeria do celular.
* **Processamento 100% Local (Privacy-First):** Nenhuma imagem ou dado do visitante é enviado para servidores externos.
* **Exportação em Alta Resolução (1080 × 1350 px):** Geração dinâmica no `<canvas>` de fichas no formato ideal para Stories do Instagram/WhatsApp, com marca oficial do Stand de Direito UNIFAN e do FINC.
* **Web Share API:** Compartilhamento direto pelo smartphone com fallback para download em `.png`.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3 Moderno** (Variáveis CSS, Dark Theme com Acentos Neon/Gold, Glassmorphism, Responsividade Mobile-First).
* **JavaScript Vanilla (ES6+)** (Canvas 2D API, Web MediaDevices API, Web Share API).
* **Zero Dependências:** Código leve, rápido e sem bibliotecas externas pesadas.

---

## 🌐 Publicação no Vercel

O projeto está pronto para deploy estático imediato no Vercel:
1. `index.html` na raiz do repositório.
2. Não requer etapa de compilação ou build (`outputDirectory: "."`).
