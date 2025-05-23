# Planejamento de Testes - Sistema de Recomendação BTG

Este documento descreve os cenários de testes dos casos de uso do sistema de recomendações para assessores de investimentos, com foco em usabilidade (baseada na Escala SUS) e nos Requisitos Funcionais (RFs) e Não Funcionais (RNFs).

## Objetivo

Validar a experiência do usuário (UX) e a conformidade funcional da plataforma, assegurando que o sistema seja eficiente, intuitivo, seguro e confiável para assessores e administradores.


## 🧪 Casos de Uso e Cenários de Teste

### 1. Autenticar Usuário
*Atores:* Assessor  
*RF/RNF Relacionados:* RNF04, RNF03  
*SUS Focado:* 4, 9

- *Cenário 1.1:* O assessor insere credenciais válidas e acessa o sistema com sucesso.
- *Cenário 1.2:* O sistema realiza autenticação via múltiplos fatores.
- *Cenário 1.3:* Verificar mensagens de erro e segurança ao inserir credenciais inválidas.

> *Testes SUS:* Avaliar sensação de segurança (confiança no sistema) e facilidade no processo de login.

---

### 2. Importar Dados de Clientes
*Atores:* Assessor  
*RF Relacionado:* RF04  
*SUS Focado:* 2, 3, 5

- *Cenário 2.1:* Upload de arquivo CSV válido com feedback de sucesso.
- *Cenário 2.2:* Upload de arquivo com erros e exibição de mensagens claras.
- *Cenário 2.3:* Tempo de resposta para uploads grandes (validar RNF05).

> *Testes SUS:* Facilidade de uso da funcionalidade, clareza das mensagens de erro e integração visual do processo.

---

### 3. Obter Dados do Cliente
*Atores:* Assessor  
*RF Relacionado:* RF01, RF07  
*SUS Focado:* 3, 5, 7

- *Cenário 3.1:* Visualização da carteira e perfil ao selecionar cliente.
- *Cenário 3.2:* Verificação de layout, organização e responsividade (RNF02).
- *Cenário 3.3:* Testar disponibilidade em diferentes horários (RNF01).

> *Testes SUS:* Facilidade de entendimento das informações exibidas e aprendizado rápido por novos usuários.

---

### 4. Comparar Perfil Calculado com Cadastrado
*Atores:* Assessor  
*RF Relacionado:* RF02, RF05  
*SUS Focado:* 1, 6, 9

- *Cenário 4.1:* Exibição clara dos perfis lado a lado.
- *Cenário 4.2:* Alertas automáticos de divergência.
- *Cenário 4.3:* Testar confiança nas recomendações apresentadas.

> *Testes SUS:* Verificar consistência do sistema e confiança nas informações.

---

### 5. Simular Ajustes na Carteira
*Atores:* Assessor  
*RF Relacionado:* RF06  
*SUS Focado:* 3, 5, 9

- *Cenário 5.1:* Simulação clara com comparativo antes/depois.
- *Cenário 5.2:* Tempo de resposta das simulações (RNF05).
- *Cenário 5.3:* Verificação de entendimento sem suporte técnico.

> *Testes SUS:* Clareza da interface, segurança nas decisões baseadas nas simulações.

---

### 6. Gerar Relatórios e Dashboards
*Atores:* Assessor  
*RF Relacionado:* RF07, RF08, RF09  
*SUS Focado:* 3, 5, 7

- *Cenário 6.1:* Aplicação de filtros e geração de dashboards.
- *Cenário 6.2:* Exportação de relatórios em diferentes formatos.
- *Cenário 6.3:* Usabilidade em dispositivos móveis (RNF02).

> *Testes SUS:* Organização e integração das informações, facilidade de uso e aprendizado.

---

### 7. Justificar Casos de Exceção
*Atores:* Assessor  
*RF Relacionado:* RF05  
*SUS Focado:* 3, 9

- *Cenário 7.1:* Inserção de justificativa em campos obrigatórios.
- *Cenário 7.2:* Validação e armazenamento correto para auditoria.
- *Cenário 7.3:* Facilidade de uso do formulário.

> *Testes SUS:* Compreensão do fluxo e confiança na integridade dos dados.

---

### 8. Gerenciar Usuários
*Atores:* Administrador  
*RF Relacionado:* —  
*SUS Focado:* 3, 6, 8

- *Cenário 8.1:* Criar, editar, desativar e reativar usuários com feedback visual.
- *Cenário 8.2:* Testar usabilidade do CRUD de usuários.
- *Cenário 8.3:* Verificar consistência do processo entre telas.

> *Testes SUS:* Facilidade de administração e consistência entre telas.

---

### 9. Configurar Parâmetros do Sistema
*Atores:* Administrador  
*RF Relacionado:* —  
*SUS Focado:* 3, 6, 10

- *Cenário 9.1:* Navegação entre categorias e edição de parâmetros.
- *Cenário 9.2:* Validação de consistência nas alterações.
- *Cenário 9.3:* Testar curva de aprendizado para configuração.

> *Testes SUS:* Facilidade de aprendizado e ausência de inconsistências na configuração.

<div align="center">
<sub>Figura 1 - Teste SUS</sub> <br>
<img src="img/PonderadaUX.png" alt="Espaçamento">
<sup>Fonte: Material produzido pelos autores (2024).</sup>
</div>

> O teste será impresso e realizado de forma presencial. O PDF pode ser encontrado [aqui](./img/Ponderada%20UX.pdf).

## Atividade desempenhada por:

- <a href="http://www.linkedin.com/in/calebe-matias">Calebe Yan Veras Matias</a>
- <a href="https://www.linkedin.com/in/fernandobertholdo/">Fernando Tavares Bertholdo</a>
- <a href="https://www.linkedin.com/in/joao-guilherme-salomao/">João Guilherme de Jesus Salomão</a>
- <a href="https://www.linkedin.com/in/lucca-henrique-pereira/">Lucca Henrique Pereira</a>
- <a href="https://www.linkedin.com/in/rafael-barbosa-b4386b293/">Rafael Rocha Barbosa</a>
- <a href="https://www.linkedin.com/in/thalyta-viana/">Thalyta da Silva Viana</a>
- <a href="https://www.linkedin.com/in/vinicius-maciel-flor/">Vinicius Maciel Flor</a>