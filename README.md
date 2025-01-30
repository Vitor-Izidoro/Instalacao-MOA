# Guia de Instalação do Massive Online Analysis (MOA) no Eclipse IDE

Este tutorial detalha o processo de instalação e configuração do **Massive Online Analysis (MOA)** no **Eclipse IDE** para desenvolvedores Java. O MOA é uma ferramenta amplamente utilizada para **mineração de dados em fluxo (stream mining)**, proporcionando um ambiente robusto para a análise de grandes volumes de dados em tempo real.

---

## 📌 Requisitos

Antes de iniciar a instalação, certifique-se de que possui os seguintes requisitos atendidos:

- **Eclipse IDE** instalado em seu sistema.
- **Java Development Kit (JDK)** atualizado.
- **Acesso à internet** para download dos arquivos necessários.

---

## 🛠 Passo a Passo

### 1️⃣ Download do MOA

1. Acesse o repositório oficial do MOA no GitHub pelo seguinte link:
   - 🔗 [https://github.com/Waikato/moa.git](https://github.com/Waikato/moa.git)

---

### 2️⃣ Importar o Projeto para o Eclipse IDE

1. Abra o **Eclipse IDE**.
2. Vá em **File** e clique em **Import**.
   
   ![image](https://github.com/user-attachments/assets/fee04bda-fc05-4a2d-b048-03f1589f2bcd)

3. Selecione **Projects from Git (with smart import)** e clique em **Next**.

   ![image](https://github.com/user-attachments/assets/1829c017-c466-46dc-be31-f6ae8e85759d)
   
   ![image](https://github.com/user-attachments/assets/7f7ec6ec-4e16-4ecf-a63f-0946bf0b2c6f)
   
   ![image](https://github.com/user-attachments/assets/b5fbd118-f7bb-4ac6-9d9c-96d2ea7f5c23)

---

### 3️⃣ Configuração de Argumentos da JVM

1. No Eclipse, clique com o botão direito no projeto e selecione **Run As** > **Run Configurations**.
   
   ![Importação](https://github.com/user-attachments/assets/c3303545-e54c-4d15-9b9e-26dd525eca5d)

2. No painel esquerdo, selecione **Java Application** e clique em **New Configuration**.
3. Vá até a aba **Arguments** e localize o campo **VM arguments**.
4. Defina a quantidade de memória RAM a ser alocada para os treinamentos do MOA. Exemplo:
   ```sh
   -Xms512m -Xmx4g
   ```
5. As demais configurações podem ser mantidas conforme os padrões do sistema.

   ![Configuração de Memória](https://github.com/user-attachments/assets/bf9021c4-e4a4-4841-a189-9083b5cced93)
   
   ![Importação 2](https://github.com/user-attachments/assets/047a27af-58b4-4ad9-a85c-851dcb9f0d43)

---

### 4️⃣ Execução do MOA

1. Com a configuração concluída, clique no botão **Run**.
2. O MOA será iniciado conforme as configurações estabelecidas.

   ![Execução](https://github.com/user-attachments/assets/1a416deb-9f79-413b-a5ee-c3f7d45089c8)

---

✅ **Parabéns!** O MOA está configurado corretamente e pronto para ser utilizado no **Eclipse** para análises online de fluxo de dados. 🚀

