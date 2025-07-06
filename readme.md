# Modelo de Relatório de Cyber Threat Intelligence (CTI)

## 📋 Descrição

Este repositório contém um modelo padronizado de relatório de Cyber Threat Intelligence (CTI) desenvolvido em LaTeX. O modelo foi criado para auxiliar analistas de segurança cibernética na documentação e comunicação eficaz de ameaças, incidentes e campanhas maliciosas.

## 🎯 Objetivo

Fornecer um template estruturado e profissional para a elaboração de relatórios CTI que atendam aos padrões da indústria, facilitando a comunicação entre equipes técnicas e stakeholders executivos.

## 📂 Estrutura do Relatório

O modelo é organizado nas seguintes seções:

### 1. **Identificação do Relatório**
- ID do Relatório (formato: CTI-AAAA-MM-###)
- Classificação da Informação (TLP)
- Data, autor(es) e contato

### 2. **Resumo Executivo**
- Descrição concisa em linguagem acessível
- Voltado para executivos e stakeholders não técnicos

### 3. **Descrição Técnica**
- Tipo de ameaça observada
- Vetores de ataque utilizados
- Alvos potenciais/afetados
- Indicadores de Comprometimento (IOCs)
- Técnicas, Táticas e Procedimentos (TTPs) baseados no MITRE ATT&CK

### 4. **Análise de Atribuição**
- Possível grupo ator
- Motivação provável
- Evidências da atribuição

### 5. **Avaliação de Impacto**
- Impacto potencial
- Probabilidade de ocorrência
- Relevância para o negócio

### 6. **Recomendações**
- Ações de contenção e mitigação
- Correções necessárias
- Boas práticas e lições aprendidas
- Sugestões de bloqueios

### 7. **Anexos**
- Logs, capturas de tela, fluxogramas
- Arquivos PCAP
- Referências externas (CVE, links OSINT)

### 8. **TLP e Política de Compartilhamento**
- Nível TLP aplicado
- Permissões de redistribuição
- Orientações para compartilhamento controlado

## 🚀 Como Usar

### Pré-requisitos
- LaTeX instalado (recomendado: TeX Live ou MiKTeX)
- Editor LaTeX (Overleaf, TeXstudio, VS Code com extensão LaTeX)

### Instruções de Uso

1. **Clone o repositório:**
```bash
git clone https://github.com/seu-usuario/cti-report-template.git
cd cti-report-template
```

2. **Compile o documento:**
```bash
pdflatex main.tex
```

3. **Personalize o conteúdo:**
   - Substitua os campos entre colchetes `[]` pelas informações específicas
   - Atualize os IOCs, TTPs e recomendações conforme necessário
   - Ajuste o nível TLP apropriado

## 📊 Exemplo de Uso

```latex
% Exemplo de preenchimento do resumo executivo
\section{Resumo Executivo}
Identificamos uma campanha de phishing visando setores de agronegócio 
do Brasil, associada ao grupo TA505. A campanha utiliza e-mails 
fraudulentos com anexos maliciosos para distribuir o malware FlawedAmmyy.
```

## 🔒 Classificação TLP

O modelo suporta os seguintes níveis de Traffic Light Protocol (TLP):

- **TLP:WHITE** - Informação pública
- **TLP:GREEN** - Compartilhamento limitado à comunidade
- **TLP:AMBER** - Compartilhamento limitado
- **TLP:RED** - Não compartilhar

## 📋 Checklist de Qualidade

Antes de finalizar seu relatório, verifique:

- [ ] Todos os campos obrigatórios foram preenchidos
- [ ] IOCs foram validados e formatados corretamente
- [ ] TTPs foram mapeados para o MITRE ATT&CK
- [ ] Nível TLP está correto
- [ ] Recomendações são acionáveis e específicas
- [ ] Gramática e ortografia foram revisadas

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-secao`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova seção'`)
4. Push para a branch (`git push origin feature/nova-secao`)
5. Abra um Pull Request

## 📝 Changelog

### v1.0.0
- Versão inicial do modelo
- Estrutura básica baseada em padrões da indústria
- Suporte a classificação TLP
- Integração com MITRE ATT&CK

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🔗 Referências

- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Traffic Light Protocol](https://www.first.org/tlp/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [SANS CTI Documentation](https://www.sans.org/white-papers/cyber-threat-intelligence/)

## 📧 Contato

Para dúvidas ou sugestões:
- LinkedIn: [Anderson Cirilo Valentim](https://www.linkedin.com/in/anderson-cirilo-valentim-a934aa15b/)
- Issues: [Link para issues do GitHub](https://github.com/andersonvalentim/LATTEX-CTI-REPORT/issues)

---

**Nota**: Este modelo foi desenvolvido seguindo as melhores práticas da indústria de segurança cibernética e pode ser adaptado conforme as necessidades específicas de cada organização.