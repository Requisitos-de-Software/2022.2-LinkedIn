# Especficação suplementar

## Histórico de Versões

**Data** | **Versão** | **Descrição** | **Autor(es/as)** | **Revisor** |
:---: | :---: | :---: | :---: | :---: |
10/12/2022 | 0.1 | Abertura do documento | Guilherme Barbosa | Pedro Moraes |

## 1. Introdução

A finalidade da Especificação suplementar é definir os requisitos não-funcionais de um sistema. É complementar ao artefato de [casos de uso](../modelagem/use-case.md), pois, juntos, são definidos os requisitos de software, funcionais e não funcionais.

## 2. Metodologia

Para definir este artefato, foi utilizado o sistema FURPS+ para definir os requisitos não-funcionais. Este modelo de definição categoriza os requisitos de acordo com os atributos de qualidade de software. As categorias são:

### **F - Funcionalidade (Functionality):** 
São os principais requisitos funcionais do produto. Os que possuem impacto arquitetural. Podem incluir:

- Conjunto de recursos 
- Recursos 
- Segurança.

### **U - Usabilidade (Usability):** 
Considera os aspectos de interatividade, design e experiência de uso. Podem incluir: 

- Fatores humanos 
- Estética
- Consistência na interface com o usuário 
- Ajuda on-line e sensível ao contexto 
- Assistentes e agentes
- Documentação do usuário 
- Materiais de treinamento

### **R - Confiabilidade (Reliability):** 
Diz respeito à disponibilidade do sistema, precisão de cálculos e tolerância a falha. Podem incluir:

- Frequência e gravidade de falha 
- Possibilidade de recuperação 
- Possibilidade de previsão 
- Exatidão 
- Tempo médio entre falhas

### **P - Desempenho (Perfomance):** 
Diz respeito à capacidade do sistema em processar tarefas com o tempo de resposta de funcionalidades, localização, encerramento e restauração de backups e falhas. Podem incluir:
    
- Velocidade
- Eficiência
- Disponibilidade
- Exatidão
- Taxa de transferência
- Tempo de resposta
- Tempo de recuperação
- Uso de recurso
  
### **S - Suportabilidade (Supportability):** 
Está relacionado à capacidade do sistema em ser testado, adaptável, mantido, compatibilizado, parametrizado, escalado, internacionalizado e implantado. Podem incluir:

- Possibilidade de teste
- Extensibilidade
- Adaptabilidade
- Manutenibilidade
- Compatibilidade
- Possibilidade de configuração
- Possibilidade de serviço
- Possibilidade de instalação
- Possibilidade de localização (internacionalização)
  
### **+ (Mais)**
O "+" relacionado no modelo FURPS+, inclui alguns requisitos como:

- **Requisitos de design:** Relacionado ao projeto do sistema. Como especificar o BD que
será utilizado.

- **Implementação:** Especifica restrições de implementação, como uso de
bibliotecas nativas ou de terceiros.

- **Interface:** Especifica integrações e acessos externos. Por exemplo,
integração via WS, REST etc.

- **Físico:** Determina restrições de hardware e implantação, por
exemplo, HD, RAM etc.