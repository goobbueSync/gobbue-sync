# 🎮 Goobbue Sync - Configuração do Cliente

Este guia explica como configurar o plugin do FFXIV para conectar ao seu servidor local Goobbue Sync.

## 🔧 Configuração Automática

O plugin já está configurado para conectar automaticamente ao seu servidor local em:
- **URL**: `ws://192.168.2.177:6000`
- **Nome**: "Goobbue Sync Local"
- **Autenticação**: Chave Secreta (não OAuth2)

## 📋 Passos para Configuração

### 1. **Instalar o Plugin**
- Baixe o plugin compilado
- Coloque na pasta `Dalamud/plugins`
- Reinicie o FFXIV

### 2. **Configurar Autenticação**
- Abra o plugin no jogo (`/goobbue`)
- Vá em **Settings** → **Server Configuration**
- Selecione "Goobbue Sync Local"
- Clique em **Add Character**
- Digite sua **Secret Key** (você receberá do servidor)

### 3. **Testar Conexão**
- O plugin deve conectar automaticamente
- Status deve mostrar "Connected"
- Outros jogadores devem aparecer na lista

## 🔑 Como Obter a Secret Key

### **Opção 1: Via Discord Bot (Recomendado)**
1. Entre no servidor Discord configurado
2. Use o comando `/register`
3. Digite sua chave de registro
4. Receba sua Secret Key

### **Opção 2: Via Interface Web**
1. Acesse `http://192.168.2.177:6000`
2. Faça login com Discord
3. Copie sua Secret Key

### **Opção 3: Direto no Servidor**
1. Execute `backup-database.bat` no servidor
2. Verifique o arquivo de backup
3. Procure pela sua Secret Key

## ⚙️ Configurações Avançadas

### **Múltiplos Servidores**
O plugin suporta múltiplos servidores:
- **Servidor Local**: `ws://192.168.2.177:6000`
- **Servidor Externo**: `ws://SEU_IP_PUBLICO:6000`
- **Servidor de Teste**: `ws://localhost:6000`

### **Configuração Manual**
```json
{
  "ServerName": "Meu Servidor",
  "ServerUri": "ws://192.168.2.177:6000",
  "UseOAuth2": false,
  "SecretKeys": [
    {
      "Key": "SUA_SECRET_KEY_AQUI",
      "FriendlyName": "Minha Chave"
    }
  ]
}
```

## 🚨 Troubleshooting

### **Plugin não conecta**
- Verifique se o servidor está rodando
- Confirme se a porta 6000 está aberta
- Teste `ping 192.168.2.177`

### **Erro de autenticação**
- Verifique se a Secret Key está correta
- Confirme se o personagem está registrado no servidor
- Tente remover e adicionar o personagem novamente

### **Outros jogadores não aparecem**
- Verifique se está conectado ao servidor
- Confirme se outros jogadores estão online
- Verifique as configurações de pairing

## 📱 Comandos do Plugin

- `/goobbue` - Abre a interface principal
- `/goobbue settings` - Abre as configurações
- `/goobbue profile` - Gerencia seu perfil
- `/goobbue pair` - Gerencia pairings

## 🔄 Atualizações

### **Atualizar Plugin**
1. Baixe a nova versão
2. Substitua o arquivo antigo
3. Reinicie o FFXIV

### **Atualizar Configuração**
1. Vá em **Settings** → **Server Configuration**
2. Clique em **Edit** no servidor
3. Atualize a URL se necessário

## 📞 Suporte

- **Issues**: Abra uma issue no repositório
- **Discord**: Entre no servidor Goobbue Sync
- **Documentação**: Consulte este README

---

**Goobbue Sync** - Deixe outros te verem como você se vê! 🎭
