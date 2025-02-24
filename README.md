# 🔍 Configurando o Azure Cognitive Search com Azure AI Services

Este projeto mostra o passo a passo para configurar uma pesquisa inteligente utilizando **Azure Cognitive Search** e **Azure AI Services**. A intenção é demonstrar como essas ferramentas podem ser integradas para criar soluções avançadas de busca, enriquecidas com inteligência artificial.

## 🚀 Passo a Passo de Configuração

### 1️⃣ Criação do Azure Cognitive Search

O primeiro passo foi criar um recurso de **Azure Cognitive Search**. Para isso:  
- Selecionei a opção de **plano básico** para começar com os recursos essenciais e custos reduzidos.  
- Configurei as opções básicas de indexação e preparei o ambiente para futuras integrações.

📸 *![image](https://github.com/user-attachments/assets/91c7db66-6d2b-4682-ac21-badab6bf45e0)
*  

> **Insight:** O Azure Search oferece uma base sólida para criar experiências de busca personalizadas, que podem ser integradas facilmente com outras ferramentas da Azure.

---

### 2️⃣ Criação do Azure AI Services Resource

Em seguida, configurei um recurso de **Azure AI Services** para adicionar funcionalidades avançadas, como análise de texto, tradução e reconhecimento de entidade.

📸 *![image](https://github.com/user-attachments/assets/02959e18-1d20-4096-91c8-6051f854d729)
*  

> **Insight:** A integração entre o Azure AI Services e o Cognitive Search amplia as possibilidades, permitindo enriquecer os resultados da pesquisa com inteligência artificial.

---

### 3️⃣ Criando uma Storage Account

Por fim, criei uma **Storage Account** para armazenar os dados que serão utilizados no processo de indexação e análise.

📸 *![image](https://github.com/user-attachments/assets/ac34b5fe-7e96-4401-855c-eae221626894)
*  

> **Insight:** Uma conta de armazenamento é essencial para gerenciar documentos, imagens e outros arquivos usados na indexação e na análise dos dados. Cada tipo de dado pode ser armazenado em um local diferente, como se fossem diferentes gavetas para cada tipo de dado.

---


### 4️⃣ Criando o Container `coffeereviews`

Com a **Storage Account** configurada, o próximo passo foi criar um container chamado `coffeereviews`. Esse container será responsável por armazenar os arquivos de revisão de cafés que serão analisados.

📸 *![image](https://github.com/user-attachments/assets/9b539067-32b0-46e9-8453-1eecfc09231b)
*  

> **Insight:** Organizar os dados em containers facilita o gerenciamento e a indexação, além de permitir o controle de permissões e acessos específicos.

---

### 5️⃣ Upload dos Arquivos de Review de Café ☕

Após configurar o container, realizei o upload dos arquivos contendo as avaliações de diferentes tipos de café. Esses arquivos serão a base para as análises de sentimento e pesquisa avançada.

📸 *![image](https://github.com/user-attachments/assets/36793903-1c36-4bc5-a440-5d8d9b4a02e1)
*  

> **Insight:** O uso de arquivos estruturados, como JSON ou CSV, facilita a leitura e indexação automática dos dados pela Azure Cognitive Search.

---

### 6️⃣ Análise de Sentimentos com o Azure Cognitive Search 🧠

Por fim, utilizei o **Azure Cognitive Search** em conjunto com o **Azure AI Services** para analisar as reviews de café e identificar sentimentos específicos (positivos ou negativos) nas avaliações.

📸 *![image](https://github.com/user-attachments/assets/d782bfde-2401-4daa-8785-b65a89339263)
*  

> **Insight:** A análise de sentimento automatizada permite entender rapidamente a percepção dos usuários sobre os produtos, sendo útil para e-commerces, plataformas de avaliação e marketing.

---

## 🔮 Possibilidades Finais

Com as análises configuradas, algumas possibilidades de uso incluem:  
- Classificação automática das melhores e piores avaliações.  
- Geração de relatórios sobre os sentimentos predominantes em relação a diferentes tipos de café.  
- Recomendação de produtos com base em sentimentos positivos das avaliações.  

---

## 📋 Conclusão

Com a configuração completa, foi possível:  
✅ Criar um motor de busca inteligente usando **Azure Cognitive Search**.  
✅ Integrar análises de sentimento com **Azure AI Services**.  
✅ Organizar dados de maneira eficiente usando uma **Storage Account**.  

---
