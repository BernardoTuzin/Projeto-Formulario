# Projeto Formulário
 
![Captura de tela 2025-01-03 180859](https://github.com/user-attachments/assets/19160381-7369-4362-814d-e716fdae5a7e)
![Captura de tela 2025-01-03 180635](https://github.com/user-attachments/assets/8d0320d8-7f03-4ce1-85f1-9fba1ef494cb)

O erro que recebi diz respeito ao fato de que o primeiro item `<option>` dentro de um `<select>` com o atributo `required` não pode ter um valor padrão (no caso, "primeiro"). Para corrigir isso, eu adicionei uma opção de **placeholder** com o valor vazio (`""`).

O erro que encontrei estava relacionado ao atributo for de alguns <label>, que precisa corresponder ao id do campo de entrada correspondente. Percebi que o for="cursos" não estava correto, pois o ID de um conjunto de checkboxes deve ser único para cada campo de seleção. Para resolver isso, eu ajustei os IDs dos campos de entrada, garantindo que cada checkbox tivesse um ID exclusivo, e então associei corretamente cada <label> ao seu respectivo campo usando o atributo for.
