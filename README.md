# FINC | Stand de Direito UNIFAN · Jogos Interativos

Aplicações web interativas desenvolvidas para o **Stand do Curso de Direito da UNIFAN (Centro Universitário Nobre)** durante o **FINC (Festival Internacional do Conhecimento)**, cujo tema oficial é **"A Era da IA: A Jornada da Inteligência Humana"**.

🔗 **Site Oficial do Festival:** [festivalfinc.com.br](https://festivalfinc.com.br/)

---

## 🎮 Jogos Disponíveis no Stand

### 1. Que Crime Tenho Chance de Cometer? (`index.html`)
* **Proposta:** Simula um algoritmo biométrico de "IA" que tira uma selfie do visitante e gera uma ficha de suspeito cômica e fictícia com pontuação de compatibilidade.
* **O Veredito:** Conduz o participante à reflexão sobre a presunção de inocência (Art. 5º, LVII da CF/88), a falácia do lombrosianismo e os riscos do viés algorítmico no reconhecimento facial.
* **Recursos:** Exportação da ficha em alta resolução (1080 × 1350 px) personalizada para postar nos Stories do Instagram.

### 2. CSI Match (`csi-match.html`)
* **Proposta:** Jogo dinâmico com mecânica de **Swipe (estilo Tinder)** onde o visitante atua como jurado criminal.
* **Dinâmica:**
  * O jogador visualiza a foto do acusado(a), a imputação penal e 4 provas periciais/testemunhais.
  * **Deslizar para a Esquerda (🛡️):** Absolver (Inocente).
  * **Deslizar para a Direita (⚖️):** Condenar (Culpado).
  * **Veredito Popular em Tempo Real:** Exibe o percentual de visitantes que votaram por condenar vs. absolver aquele réu.
  * **10 Casos Reais/Simulados:** 5 homens e 5 mulheres com dilemas jurídicos modernos (crimes cibernéticos, deepfake de voz, legítima defesa, LGPD, dano ao patrimônio, etc.).
  * **Perfil de Juiz:** Ao final dos 10 casos, classifica o jogador em perfis jurídicos (*Garantista Constitucional*, *Magistrado Equilibrado* ou *Punitivista Cauteloso*).
* **Áudio Dinâmico:** Efeitos sonoros sintetizados via Web Audio API (sem dependências de áudio externas).

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
