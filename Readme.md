#VM Azure

## 🧭 Etapa 1: Acesso aos Serviços do Azure

📌 *Imagem: "Todos os serviços"*

- Acesse o portal do Azure.
- No menu lateral, clique em **"Todos os serviços"**.
- Localize e selecione **"Máquinas virtuais"** na categoria *Computação*.

🔲 *Confirmação visual*: O serviço "Máquinas virtuais" está destacado com marcação em preto.

---

## 🖥️ Etapa 2: Acesso à Infraestrutura de Computação

📌 *Imagem: "Infraestrutura de computação | Máquinas virtuais"*

- No menu lateral, vá até **"Infraestrutura"**.
- Clique em **"Máquinas virtuais"** para visualizar ou criar novas VMs.

🔲 *Dica*: A descrição indica que VMs são ideais para cargas leves, testes ou personalizações profundas. Caso o tráfego aumente, é possível migrar para um VMSS.

---

## 🆕 Etapa 3: Iniciar Criação de Máquina Virtual

📌 *Imagem: "Máquinas virtuais – sem instâncias"*

- Na tela principal de VMs, clique no botão **"Criar"** (com seta para baixo).
- Escolha **"Máquina virtual"** para iniciar o provisionamento.

🔲 *Observação*: A interface mostra que não há VMs criadas ainda. O botão "Criar" está destacado.

---

## ⚙️ Etapa 4: Configuração Básica da Máquina Virtual

📌 *Imagem: "Criar Máquina Virtual – Aba Básico"*

- **Assinatura**: Selecione *Azure subscription 1*.
- **Grupo de recursos**: Crie ou selecione (ex: *VMTeste*).
- **Nome da VM**: Defina (ex: *VMTestes*).
- **Região**: Escolha *(Africa) South Africa North*.
- **Opções de disponibilidade**:  
  - Selecione *Zona de disponibilidade*.  
  - Escolha *Zona auto-selecionada*.

🔲 Após preencher os campos, clique em **"Avançar: Discos"** ou **"Revisar + criar"**.

---

## 📈 Etapa 5: Provisionamento de VMSS (Conjunto de Dimensionamento)

📌 *Imagem: "Criar VMSS – Aba Revisar + criar"*

- **Assinatura**: *Azure subscription 1*  
- **Grupo de recursos**: *(novo) VMTeste*  
- **Nome do VMSS**: *VMTestes*  
- **Região**: *East US*  
- **Modo de orquestração**: *Flexível*  
- **Zona de disponibilidade**: *Nenhum*  
- **Imagem**: *Ubuntu Server 24.04 LTS – Gen2*  
- **Tamanho**: *Standard D2s v3 (2 vcpus, 8 GiB memória)*  
- **Modo de dimensionamento**: *Atualizar manualmente a capacidade*  
- **Contagem de instâncias**: *1*

