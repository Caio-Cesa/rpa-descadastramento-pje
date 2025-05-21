# Automação de Descadastramento no PJe – TRF1 (1ª e 2ª Instância)
🗓️ Projeto desenvolvido em: Setembro de 2021

Este projeto automatiza o processo de **descadastramento de advogados e partes em processos judiciais eletrônicos** no sistema PJe da Justiça Federal da 1ª Região (TRF1), tanto na 1ª quanto na 2ª instância.

## 💼 Contexto

Desenvolvido para um escritório de advocacia, o processo manual de descadastramento no PJe era extremamente repetitivo, sujeito a erros humanos e tomava tempo da equipe jurídica e administrativa.

A automação foi criada com **Macro Scheduler**, integrando ações entre:
- Google Chrome (navegação e interação com o PJe)
- Excel (gerenciamento dos dados)
- OCR por imagem (reconhecimento de elementos visuais na tela)

## 🎯 Objetivos

- Eliminar a repetição manual de comandos como clique, navegação por abas e cópia de informações.
- Acelerar o fluxo de descadastramento de processos.
- Reduzir riscos de erro humano durante o procedimento.
- Gerar evidências (prints) e registrar status em planilha.

## 🧩 Tecnologias utilizadas

- [Macro Scheduler](https://www.mjtnet.com/) – linguagem de automação para Windows
- Excel – integração e leitura de dados
- Reconhecimento por imagem (BMP) – para identificar pontos-chave da interface do PJe

## 🛠️ Funcionalidades

- Navega automaticamente até o processo no site do PJe
- Realiza comandos de clique e teclas para acessar o processo
- Executa o descadastramento via interface simulada
- Captura tela como comprovante de execução
- Registra a movimentação na planilha Excel do sistema interno do escritório

## ⚙️ Exemplo de fluxo

1. Copia o número do processo a partir do Excel
2. Acessa o site do TRF1
3. Preenche automaticamente os campos até encontrar o processo
4. Acessa o processo e executa o descadastramento
5. Salva a movimentação e retorna ao Excel

## 📊 Impacto

- Redução do tempo de execução manual para menos de **1 minuto por processo**
- Geração automática de comprovante
- Mais de **400 processos tratados em lote com mínima intervenção humana**

## ⚠️ Aviso

Este projeto é uma automação voltada para um ambiente específico e depende de:
- Configuração de telas idênticas à da máquina onde foi desenvolvida
- Caminhos corretos para imagens `.bmp` de referência
- Permissões de acesso ao PJe e Excel

---

📌 Projeto de uso interno e educativo.  
**Desenvolvido por Caio Cesar de Albuquerque**  
📫 [caioalbuquerquedev@gmail.com](mailto:caioalbuquerquedev@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/caio-cesar-for-hire) | [GitHub](https://github.com/Caio-Cesa)
