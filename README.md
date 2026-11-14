Meu Portfólio

## Nome do Aluno
Pietra de Souza Felix

## Descrição do Portfólio
Este projeto consiste em um portfólio web pessoal, desenvolvido para apresentar minha trajetória, habilidades técnicas e principais projetos realizados ao longo do curso de desenvolvimento de sistemas. O site foca em uma experiência limpa, intuitiva e totalmente responsiva.

## Tecnologias Utilizadas
- **HTML5** (Estruturação semântica)
- **CSS3** (Estilizações avançadas e animações)
- **GitHub** (Versionamento e hospedagem)


## Explicação do Funcionamento do Projeto
O site está estruturado em uma única página (*Single Page Application*) com rolagem suave (*smooth scroll*):
1. **Menu de Navegação:** Fixo no topo e responsivo, permitindo alternar rapidamente entre as seções de Perfil, Habilidades, Projetos e Contato.
2. **Seção de Perfil:** Apresenta uma introdução visual marcante e um botão de chamada para ação (*call to action*) direcionando para os projetos.
3. **Seção de Habilidades:** Exibe os conhecimentos técnicos em cards organizados através do sistema de grade (*Grid*) do Bootstrap.
4. **Seção de Projetos:** Destaca os principais trabalhos acadêmicos desenvolvidos.
5. **Seção de Contato:** Canal direto para comunicação e envio de e-mail.

## Descrição do Recurso Novo Adicionado
Como recurso adicional exigido na atividade, foi desenvolvida uma **Seção de Habilidades Interativas com Efeito de Hover Avançado (`.skill-card:hover`)**.

## Explicação de Como Esse Recurso Foi Implementado
O recurso foi criado unindo classes utilitárias do Bootstrap para cartazes (`card`, `shadow-sm`, `p-3`) a regras customizadas no arquivo `style.css`:
- Utilizou-se a propriedade `transition: transform 0.3s ease, box-shadow 0.3s ease;` para garantir suavidade nas transições visuais.
- Na pseudo-classe `:hover`, a propriedade `transform: translateY(-8px);` faz com que o card se eleve sutilmente quando o cursor passa por cima, enquanto o `box-shadow` é intensificado para simular profundidade e interatividade.
