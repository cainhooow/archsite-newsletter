Fala, arqueiros! Aqui vai uma curiosidade:

ArchGTi existe desde 2020, quando se chamava "Drkryz Project", que ainda é mantido como parte de desenvolvimento de projetos. As primeiras contribuições do projeto foram em 2021, com o desenvolvimento de um tema (Drkryz Theme) para desenvolvedores no VSCode, com cores suaves e minimalistas.

O nosso site existe desde 2023, com base fechada e sendo desenvolvido ao longo do tempo, sem o objetivo de ser "ArchGTi". Usamos uma stack desde 2023 — NextJS + Supabase, sendo o NextJS toda a parte funcional e Supabase o nosso banco de dados, onde todas as suas informações permanecem persistentes, com segurança e monitoramento diários contra vazamentos e tentativas de invasões. Usamos a linguagem de programação TypeScript juntamente com o runtime do Bun, que antes era NodeJS.

Parte do site tem serviços separados, sendo eles feitos na linguagem de programação Rust, que, de uns anos para cá, se tornou a linguagem main do projeto. Seguimos uma estrutura de feature-based, para futuramente abrir o código do projeto e a comunidade poder desenvolver cada módulo separado da base principal, ou se basear na estrutura, inclusive algumas partes, já sendo open source (código aberto).

Na antiga newsletter foi usada uma stack PHP + Laravel, hospedada na Azure, porém não teve sucesso e o projeto foi descontinuado, tendo apenas a base open-source dele.

O site é desenvolvido em uma "caixa de areia", que simula o mundo real isoladamente, para testar a segurança e implementação de novos recursos. Usamos uma stack de desenvolvimento back-end: Postman + Docker e Podman, com caixas de areia do Distrobox Usamos o Arch Linux como sistema operacional padrão, com algumas bases feitas no Windows. Cada sistema operacional tem suas vantagens.

O trabalho da Arch é manter o site sempre o mais otimizado possível, levando como regra o código limpo e uma estrutura legível. O site usa técnicas de cache para não sobrecarregar o servidor, então, se você já abriu uma página antes, partes dela ficam salvas em seu dispositivo, sendo mais rápido em uma próxima vez que você abrir a mesma página, e o NextJS entrega exatamente o que precisa: otimizações de imagens e cache, carregamentos parciais, etc.

Por mais que a estrutura tenha serviços separados, a base é monolítica; isso significa que todo o código é concentrado em apenas um projeto, resumidamente, o famoso "faz tudo".

Para sempre manter a plataforma funcionando, seguimos com planos de desenvolvimento: mapear o sistema, escrever tarefas e determinar a prioridade, aplicar a tarefa no projeto, revisar e subir para a base principal (fora da caixa de areia) e ir para todos vocês poderem usar.

Não só isso: os planos de desenvolvimento têm regras rígidas. Se um teste falhar, tanto na questão de bugs quanto na questão de segurança, ele nem sai da "caixa de areia".

E tudo isso de forma gratuita, sem lucros e apenas investimentos. Desde que o projeto se chamava "Drkryz Project", tivemos uma margem de 0% em lucros, pois todos os projetos foram feitos para a comunidade, sem visar o dinheiro. Era apenas contribuição de ideias que ou deram certo ou viraram um arquivamento.

A newsletter é uma forma de podermos entregar esses mesmos conteúdos, de graça e com coisas que podem fazer a diferença e despertar ideias, sem que você precise ser cliente para isso. Queremos incluir e mostrar como é todo o funcionamento desse pequeno site, que é a nossa casa.
