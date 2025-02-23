# 🎙️ Análise de Sentimentos com Azure AI

Este projeto foi desenvolvido para demonstrar a aplicação de **Azure AI** no processamento de linguagem natural (NLP), utilizando **Speech Studio** e **Language Service** para converter áudio em texto e analisar sentimentos.

## 📂 Estrutura do Projeto

- **`inputs/`** – Contém os arquivos de texto gerados a partir do áudio.  
- **`readme.md`** – Documentação e descrição do processo.  

## 🚀 Como foi o Processo

### 1️⃣ Conversão de Áudio em Texto

Utilizei o **Speech Studio** da Azure para converter meu arquivo de som `bad_habits.mp3` em texto. O resultado da conversão pode ser visto abaixo:

📸 *![image](https://github.com/user-attachments/assets/1aca623f-ca1e-4ed2-a7b7-5ca6b0270383)*  
  

> **Insight:** Durante esse processo, percebi que a ferramenta lida muito bem com diferentes sotaques e variações de pronúncia, resultando em uma transcrição precisa.

---

### 2️⃣ Configuração do Azure Language Service

Em seguida, criei meu próprio serviço de **Azure AI Language** para avaliar os sentimentos do texto extraído. O serviço foi configurado para identificar emoções como positivo, negativo e neutro.

📸 *![image](https://github.com/user-attachments/assets/142aabf1-29fb-4c51-8f34-7e0303d2f21a)
*  

> **Insight:** A configuração do serviço foi simples, e a documentação da Azure facilitou a integração com o texto gerado pelo Speech Studio.

---

### 3️⃣ Análise de Sentimento do Texto

Com o texto extraído, apliquei a análise de sentimento, obtendo um resultado detalhado sobre as emoções predominantes nas frases.

📸 *[![image](https://github.com/user-attachments/assets/84f57f9c-c869-4628-a4bb-3ca45b0f491a)

> **Insight:** A análise foi capaz de identificar nuances de sentimento em frases mais complexas, o que abre possibilidades para aplicações em feedbacks automáticos, análises de reviews e muito mais.

---

## 💡 Possibilidades Futuras

- 🔍 Implementar uma análise de palavras-chave para entender os principais tópicos abordados no áudio.  
- 📊 Integrar um painel visual (dashboard) para exibir os resultados de forma mais interativa.  
- 🤖 Aplicar um modelo de machine learning para melhorar a precisão da análise de sentimentos.  

---

## 📸 Prints e Resultados

Adicionei capturas de tela de cada etapa para ilustrar o processo e os resultados obtidos.


---
