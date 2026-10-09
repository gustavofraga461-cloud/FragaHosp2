# FragaHosp — versão estática para Render

## Publicar no Render sem banco de dados
1. Envie `index.html` para um repositório GitHub.
2. No Render, crie um **Static Site** conectado a esse repositório.
3. Deixe **Build Command** vazio.
4. Defina **Publish Directory** como `.`
5. Clique em **Create Static Site**.

## Limitações importantes
Esta versão não usa banco de dados. Os agendamentos ficam no `localStorage` do navegador/dispositivo. Portanto, não são compartilhados entre computadores/celulares e podem ser perdidos se os dados do navegador forem apagados. Ela é adequada para demonstração/testes, não para dados reais de pacientes.
