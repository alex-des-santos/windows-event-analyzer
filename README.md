# 📊 Windows Event Log Analyzer

Uma ferramenta web moderna e intuitiva para análise de logs do Event Viewer do Windows, com insights inteligentes gerados por IA.

🌐 **[Acesse a ferramenta online](https://alex-des-santos.github.io/windows-event-analyzer/)**

📂 **[Repositório GitHub](https://github.com/alex-des-santos/windows-event-analyzer)**

## ✨ Funcionalidades

### 📈 Análise Automática
- **Estatísticas detalhadas**: Total de eventos, erros, avisos e informações
- **Principais fontes**: Identificação dos serviços/aplicativos mais ativos
- **Top erros**: Lista dos erros mais frequentes com descrições
- **Intervalo temporal**: Análise do período coberto pelos logs

### 🤖 Insights com IA
- **Análise inteligente**: Powered by Google Gemini AI
- **Problemas críticos**: Identificação automática de issues importantes
- **Soluções práticas**: Recomendações específicas para correção
- **Prevenção**: Sugestões para evitar problemas futuros
- **Status do sistema**: Avaliação geral da saúde do Windows

## 🚀 Como Usar

1. **Exporte seus logs do Event Viewer**:
   - Abra o Event Viewer do Windows
   - Selecione "Windows Logs" > "Application" ou "System"
   - Clique com botão direito > "Save All Events As..."
   - Escolha formato CSV

2. **Acesse a ferramenta**: [Windows Event Log Analyzer](https://alex-des-santos.github.io/windows-event-analyzer/)

3. **Configure a API**: 
   - Obtenha uma API key gratuita no [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Cole a chave no campo correspondente

4. **Carregue os logs**: Arraste e solte ou selecione arquivos CSV

5. **Analise**: Clique em "Analisar Logs" para obter insights

## 🔧 Requisitos

- **Navegador moderno** com suporte a JavaScript ES6+
- **Conexão com internet** para acessar a API do Google AI Studio
- **API Key do Google AI Studio** (gratuita)

## 📋 Arquivos de Exemplo

O repositório inclui arquivos CSV de exemplo para teste:
- `Aplicativo.csv` - Logs de aplicativos (~500KB)
- `Sistema.csv` - Logs do sistema (~2.8MB)

## 🔒 Segurança e Privacidade

- ✅ **Processamento local**: Arquivos não são enviados para servidores
- ✅ **API segura**: Comunicação criptografada com Google AI Studio
- ✅ **Sem armazenamento**: Dados não são salvos permanentemente
- ⚠️ **API Key**: Mantenha sua chave privada e segura

## 🛠️ Tecnologias

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **IA**: Google Gemini API
- **Hospedagem**: GitHub Pages
- **Processamento**: 100% client-side

## 📊 Exemplo de Análise

A ferramenta gera relatórios detalhados como:

```json
{
  "resumo_geral": "Sistema apresenta 245 erros críticos...",
  "problemas_criticos": [
    {
      "titulo": "Falhas de Driver",
      "descricao": "Driver de áudio apresentando instabilidade",
      "impacto": "Pode causar travamentos do sistema",
      "solucao": "Atualizar driver via Device Manager"
    }
  ],
  "status_sistema": "Atenção"
}
```

## 🤝 Contribuindo

1. Fork o projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🆘 Suporte

Encontrou um bug ou tem uma sugestão? [Abra uma issue](https://github.com/alex-des-santos/windows-event-analyzer/issues)

---

**Desenvolvido com ❤️ para análise eficiente de logs do Windows**