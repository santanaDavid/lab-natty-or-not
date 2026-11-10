# Roteiro de Podcast: Specification Data-Driven em IA

**Duração estimada:** 3 minutos  
**Formato:** Monólogo objetivo / Apresentação de trabalho  
**Público-alvo:** Estudantes e Profissionais de Tecnologia  

---

## Roteiro

### [00:00 - 00:30] Introdução e Definição
* **Host:** "Olá, pessoal! Sejam bem-vindos a este podcast sobre **Specification Data-Driven** em Engenharia de Software e IA."
* **Host:** "Quando desenvolvemos sistemas de Inteligência Artificial, um dos maiores erros é definir especificações baseadas em achismos ou prompts estáticos. A *Specification Data-Driven* (ou Especificação Guiada por Dados) é a prática de usar evidências, telemetria e dados reais de execução para definir os requisitos, contratos e o comportamento esperado do sistema."

### [00:30 - 01:45] O Problema e os Pilares
* **Host:** "Modelos de IA são probabilísticos e não-determinísticos. Isso significa que eles não seguem regras condicionais simples como `if/else`. Sem dados de uso real, é impossível garantir a confiabilidade."
* **Host:** "Para aplicar esse conceito, nós nos baseamos em três pilares essenciais:"
  1. **Contratos e Schemas Rigorosos:** Definir estruturas explícitas de dados (como JSON Schema ou Pydantic) para validar tudo o que entra e sai do modelo.
  2. **Telemetria Contínua:** Monitorar logs de uso, latência, desalinhamentos semânticos e taxas de erro em produção.
  3. **Datasets de Avaliação (Evals):** Criar conjuntos de testes baseados em cenários reais para garantir que atualizações no sistema não quebrem o comportamento esperado.

### [01:45 - 02:30] O Ciclo de Desenvolvimento
* **Host:** "Na prática, o desenvolvimento deixa de ser estático e vira um loop contínuo: você lança uma especificação inicial, analisa as divergências nos dados de execução e usa essas falhas reais para refinar as instruções e travar as regras do sistema."

### [02:30 - 03:00] Conclusão
* **Host:** "Em resumo: a *Specification Data-Driven* transforma respostas imprevisíveis de IA em componentes de software confiáveis e mensuráveis. Muito obrigado pela atenção e até a próxima!"
