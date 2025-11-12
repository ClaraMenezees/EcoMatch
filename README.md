# 🌱 EcoMatch

### Conectando pessoas para um descarte consciente de resíduos

---

## 📘 Descrição do Projeto

O **EcoMatch** é um aplicativo Android desenvolvido com o objetivo de **facilitar o descarte e a reutilização de resíduos** de forma sustentável.  
A plataforma conecta pessoas que possuem resíduos (como óleo de cozinha usado, pilhas, eletrônicos, plásticos contaminados, tecidos, entre outros) com **coletores, recicladores e empreendedores** que desejam reaproveitar esses materiais.

Assim, o aplicativo contribui para a **redução do descarte incorreto**, incentiva a **economia circular** e promove uma **conscientização ambiental** dentro das cidades.

---

## 🌍 Problema e Solução Proposta

- **Problema:** muitas pessoas armazenam grandes quantidades de resíduos domésticos (como óleo usado) sem saber como descartá-los corretamente. Isso gera contaminação ambiental e desperdício de recursos reaproveitáveis.  
- **Solução:** criar um app que **intermedeie a comunicação entre doadores e coletores**, permitindo o **cadastro, busca e negociação de resíduos recicláveis ou reaproveitáveis**, além de **mostrar pontos de coleta** e **oferecer dicas de sustentabilidade**.

---

## 👩‍💻 Equipe de Desenvolvimento

| Integrante         | Função | Responsabilidades |
|-------------------|---------|-------------------|
| Silvio Marques    | Desenvolvedor(a) Android | Implementação da UI, Navigation, ViewModels |
| Edvaldo Luiz      | Desenvolvedor(a) Backend/API | Integração e endpoints REST |
| nyckollas Paulino | Designer UX/UI | Protótipos, acessibilidade e responsividade |
| Clara Menezes     | Tester / Documentação | Testes, README, organização do repositório |

---

## 🏗️ Arquitetura e Tecnologias

### 🔹 Arquitetura
O app segue o padrão **MVVM (Model–View–ViewModel)**, garantindo separação de responsabilidades, testabilidade e manutenção do código.

### 🔹 Tecnologias Utilizadas
- **Linguagem:** Kotlin  
- **Arquitetura:** MVVM  
- **Comunicação Reativa:** StateFlow / SharedFlow  
- **Tratamento de eventos únicos:** SharedFlow e SingleLiveEvent  
- **UI:** RecyclerView, Fragments, Navigation Component (Safe Args)  
- **API REST:** Retrofit + Coroutines  
- **Banco local:** Room (cache offline)  
- **Gerenciamento de escopo:** viewModelScope  
- **Acessibilidade:** Labels, contentDescription, contraste e navegação por teclado  
- **Controle de versão:** Git + GitHub (branches e PRs)  

---

## 📱 Funcionalidades Principais

- ✅ Cadastro de resíduos (foto, tipo, quantidade e localização)  
- 🔍 Busca e filtro por tipo de resíduo ou proximidade  
- 🗺️ Mapa com anúncios e pontos de coleta  
- 💬 Contato entre usuários (chat ou telefone/email)  
- ♻️ Histórico de coletas e anúncios  
- 🌿 Dicas de sustentabilidade diárias 
