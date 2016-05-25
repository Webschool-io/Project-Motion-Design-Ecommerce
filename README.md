# Project Motion Design Ecommerce

Ideias de UX para ecommerce utilizando micro animações para que elas atuem como feedback de ações e **também** para chamar a atenção do usuário para qual a póxima açao que ele deve fazer.

## Forms

O botão de CADASTRAR/ALTERAR devem sempre vir desabilitados e a cada campo preechido corretamente o botão vai mostrando o progresso do usuário como se fosse uma progress bar.

## Campos

Todos que são obrigatórios são mostrados com uma borda em vermelhor que só mudará para verde depois de validado seu valor, caso seja inválido o campo deverá executar uma animação que traga o foco do usuário para aquele campo.

## Botões

Os botões devem ficar desabilitado por padrão e só mudam de estado após suas regras serem validadas.

Exemplo:

Botão de COMRAR só pode ser habilitado depois de escolher o produto e quantidade.

O [codepen.io]() tem um ótimo exemplo disso quando ele salva seu código automaticamente, la no topo, o botão `save` vai pro lado e volta.

### Animação

Quando o botão mudar de estado ele não mudará apenas de cor mas também terá algum tipo de animação para chamar a atenção do usuário.

## Carrinho

A cada produto adicionado no carrinho ele pode tanto sair da page e ir até o carrinho ou apenas mudar o icone mostrando a quantidade de produtos e a cada adição deve ocorrer uma animação que mostre para o usuário o feedback da ação.

Mostrar a listagem dos produtos quando o usuário deixar o mouse em cima do ícone para que não precise sair da página para conferir seu carrinho.

## Busca

A busca deve ser instantanea e filtrar os produtos via AJAX sem precisar sair daquela página.
