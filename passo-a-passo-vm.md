# 👣 Passo a Passo: Criando uma Máquina Virtual no Microsoft Azure

## 1️⃣ Acessar o Portal Azure
- Vá até: https://portal.azure.com

## 2️⃣ Criar um Novo Recurso
- Clique em "Criar um recurso" > "Computação" > "Máquina Virtual".

## 3️⃣ Configurar a VM
- **Nome**: ex: `vm-estudos-dio`
- **Região**: ex: "Brasil Sul"
- **Imagem**: Ubuntu 20.04 LTS ou Windows Server 2019
- **Tamanho**: B1s (econômico para testes)
- **Autenticação**: senha ou chave SSH
- **Portas abertas**: RDP (para Windows) ou SSH (para Linux)

## 4️⃣ Configurações Avançadas
- Criar novo grupo de recursos
- Configurar disco (padrão ou SSD)
- Opções de backup (opcional)

## 5️⃣ Revisar e Criar
- Clique em “Revisar + Criar”
- Após a validação, clique em “Criar”

## 6️⃣ Conectar à VM
- Após o provisionamento, vá até o recurso
- Use o botão “Conectar” e siga as instruções para RDP ou SSH

## 7️⃣ Monitorar e Gerenciar
- Utilize o painel para reiniciar, parar, redimensionar ou excluir a VM.
