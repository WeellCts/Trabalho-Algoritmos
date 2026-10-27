
```markdown
# Relatório de Respostas Teóricas

## Seção 1: Análise da Aula

1. **Por que utilizamos laços de repetição?**  
   Utilizamos laços de repetição (como for, while e do-while) para automatizar tarefas repetitivas e evitar a duplicação de código, aplicando o princípio DRY (Don't Repeat Yourself). Eles permitem executar um bloco de código múltiplas vezes de forma eficiente até que uma condição lógica seja atingida

2. **Qual é a diferença entre `while` e `do-while`?**  
   while: Testa a condição antes de executar o bloco. Se a condição for falsa inicialmente, o código interno não é executado nenhuma vez.

    do-while: Executa o bloco de código pelo menos uma vez antes de testar a condição no final.

Exemplo de situação importante: Validação de entrada de usuário (ex: menu interativo). O programa precisa exibir o menu e capturar a escolha do usuário pelo menos uma vez antes de verificar se ele deseja sair.

3. **Por que são necessários dois laços no exemplo dos times?**  
   Em problemas de cruzamento ou combinações (como gerar todas as partidas de um campeonato onde todos jogam contra todos), precisamos de dois laços aninhados: o laço externo define o primeiro time (mandante) e o laço interno percorre novamente a lista para definir o segundo time (visitante), cobrindo todas as permutações possíveis entre os elementos.

4. **Qual a função do `if` que impede confrontos próprios?**  
  A instrução condicional (por exemplo, if (i != j)) garante que os índices dos dois times sejam diferentes, evitando que um time jogue contra si mesmo (como o "Time A" enfrentando o "Time A").

5. **Diferenças e semelhanças entre Java, C# e Rust:**  
   - *Diferenças:* Sintaxes de declaração/métodos (`.length` vs `.Count` vs `.len()`) e adição dinâmica.
   - *Semelhança:* O raciocínio lógico de laços aninhados e restrição condicional permanece idêntico.

---

## Seção 2: Leitura do Livro (Entendendo Algoritmos)

1. **Como elementos do Array são organizados e acessados?**  
   

2. **Como elementos de uma lista encadeada são organizados?**  
   

3. **Inserção/Exclusão:**  
   

4. **`List<string>` (C#) e `Vec<String>` (Rust) são listas encadeadas?**  
   

5. **Vantagens do Array para percorrimento:**  
   
---

## Seção 4: Alteração da Coleção

1. **Por que o array de Java exigiu outro array?**  
   

2. **O que ficou mais simples com `List` e `Vec`?**  
   

3. **Facilidade de adicionar significa ser lista encadeada?**  
   

---

## Seção 7: Participação da Dupla e Registro

- **Erro Encontrado e Solução:** Ao criar a tabela de turno único, inicialmente ocorriam duplicatas invertidas. O erro foi corrigido ajustando o início do laço interno para `j = i + 1`.

- **Contribuição Integrante 1:** Implementou as versões em C# e Rust e executou o teste de mesa.

- **Contribuição Integrante 2:** Desenvolveu a lógica inicial em Java e estruturou o README do repositório.

- **Uso de IA:** Utilizado o ChatGPT/Gemini para auxílio na estruturação inicial dos scripts e revisão dos conceitos de gerenciamento de memória.