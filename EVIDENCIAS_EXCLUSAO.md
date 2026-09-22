# Evidências da Funcionalidade de Exclusão com Confirmação

Este documento apresenta a sequência de evidências da implementação do fluxo de exclusão segura de tarefas com diálogo de confirmação (Jetpack Compose Material 3).

---

### 1. Lista antes da exclusão
Exibição da lista de tarefas cadastradas antes de acionar a exclusão.

![1. Lista antes da exclusão](docs/images/exclusao/01_lista_antes.png)

---

### 2. Diálogo aberto com a tarefa selecionada
Ao tocar no ícone de lixeira, o diálogo de confirmação do Material 3 é exibido sobre a tela da lista, informando claramente o título da tarefa selecionada.

![2. Diálogo aberto com a tarefa selecionada](docs/images/exclusao/02_dialogo_aberto.png)

---

### 3. Resultado ao cancelar
Ao acionar o botão **Cancelar**, o diálogo é fechado e a lista permanece inalterada sem remover nenhuma tarefa.

![3. Resultado ao cancelar](docs/images/exclusao/03_resultado_cancelar.png)

---

### 4. Nova abertura do diálogo
Reabertura do diálogo de confirmação para a mesma tarefa selecionada para confirmar a remoção.

![4. Nova abertura do diálogo](docs/images/exclusao/04_reabertura_dialogo.png)

---

### 5. Resultado após confirmar a exclusão
Ao acionar o botão **Excluir**, a tarefa selecionada é definitivamente removida e o diálogo é fechado, atualizando a lista.

![5. Resultado após confirmar a exclusão](docs/images/exclusao/05_resultado_confirmar.png)
