
# Reunião 2: 25/04/2025

## Introdução

Este artefato resume a reunião do dia 25 de Abril de 2025 do grupo 06, nele está contido os principais objetivos e as questões que a equipe debateu e executou, bem como os resultados obtidos.

***

## Pautas da reunião:


- Análise e revisão do diagrama de classes inicial

- Validação das entidades e seus atributos

- Verificação de heranças, composições e relacionamentos

*** 

## Integrantes presentes:

Todos os integrantes participaram.

<label><input type="checkbox" checked disabled>[Diego Carlito](https://github.com/DiegoCarlito)</label><br>
<label><input type="checkbox" checked disabled>[Filipe Carvalho](https://github.com/Filipe-002)</label><br>
<label><input type="checkbox" checked disabled>[Genilson Silva](https://github.com/GenilsonJrs)</label><br>
<label><input type="checkbox" checked disabled>[Geovane Freitas](https://github.com/GeovaneSFT)</label><br>
<label><input type="checkbox" checked disabled>[Guilherme Coelho](https://github.com/Guilermanoo)</label><br>
<label><input type="checkbox" checked disabled>[Gustavo Alves](https://github.com/gustaallves)</label><br>
<label><input type="checkbox" checked disabled>[João Vitor](https://github.com/Joa0v)</label><br>
<label><input type="checkbox" checked disabled>[Marcos Castilhos](https://github.com/Marcosatc147)</label><br>
<label><input type="checkbox" checked disabled>[Nicollas Gabriel](https://github.com/Nicollaxs)</label><br>
<label><input type="checkbox" checked disabled>[Pedro Henrique](https://github.com/PedroHhenriq)</label><br>
<label><input type="checkbox" checked disabled>[Samuel Ribeiro](https://github.com/SamuelRicosta)</label><br>

***

## Informações da reunião

<font size="2" >
<p> Tabela 1: Informações da reunião. </p>
</font>

| Data | Início | Fim | Local |
|:-:|:-:|:-:|:-:|
| 25/04/2025  | 20:00 | 21:00  | Teams |

***

## Discussões Realizadas

Durante esta etapa do projeto, os participantes se reuniram com o objetivo de elaborar e
revisar o diagrama de classes previamente elaborado, garantindo que as entidades
estivessem bem definidas, completas e adequadas ao escopo do sistema, baseando-se
também no DER elaborado por cada membro do grupo.

Foram analisados os seguintes pontos:
- Consistência na modelagem de atributos
- Inclusão de herança entre classes
- Correções nos relacionamentos (um-para-muitos, muitos-para-muitos, etc.)
- Agrupamento de atributos comuns e eliminação de redundâncias

*** 

## Decisões Tomadas

1. **Confirmação da Entidade Abstrata `Usuário`:**
    - Manteve-se como entidade base para especializações futuras (como administrador, consumidor, produtor).
    - Reforçada a presença dos atributos: nome, email, senha, profissão, idade, ranking, foto de perfil, biografia, permissões e cidade.

2. **Entidade `Café`:**
    - Validação dos atributos: nome, tipo, região, métodos de preparo (mantido como multivalorado).
    - Foi sugerida a possibilidade futura de relacionar cafés com produtores.

3. **Entidade `Receita`:**
    - Atributos discutidos e definidos para incluir: nome, descrição, ingredientes, modo de preparo, autor.


4. **Entidade `Postagem`:**
    - Confirmada com campos como título, conteúdo, data, autor.

5. **Entidade `Tópico`:**
    - Relacionada a categorias de discussão e comentários.

6. **Entidade `Evento`:**
    - Representa encontros ou experiências com café; atributos: nome, data, local, organizador, participantes.

7. **Entidade `Interações`:**
    - Agrega curtidas, comentários e avaliações de usuários sobre conteúdo do sistema.

***

## Encaminhamentos

- **Filipe, Geovane e Marcos** ficarão responsáveis por finalizar e otimizar o diagrama.
- Todos os participantes deverão revisar as classes atribuídas e validar coerência com os casos de uso definidos no sistema.

***

**Encerramento**:  A reunião foi encerrada às 21h00, com consenso entre todos os participantes sobre os pontos discutidos

***

## Gravação da reunião

<div style= "max-width:450px">
<iframe src="https://unbbr.sharepoint.com/sites/ArquiteturaeDesenhodeSoftwareGrupo06539/_layouts/15/embed.aspx?UniqueId=14fe51e6-e1d4-4fe7-b22e-148126558d90&embed=%7B%22ust%22%3Atrue%2C%22hv%22%3A%22CopyEmbedCode%22%7D&referrer=StreamWebApp&referrerScenario=EmbedDialog.Create" width="560" height="315" frameborder="0" scrolling="no" allowfullscreen title="Reunião 2 - Entrega 2 - Diagrama de Classes-20250425_191129-Gravação de Reunião 1.mp4"></iframe>
</div>

***

## Histórico de Versão

| Versão | Data | Descrição | Autor | Revisor|Detalhes da Revisão|
|:-:|:-:|:-:|:-:|:-:|:--:|
|`1.0`| 08/05/2025 | Criação do documento| [Filipe Carvalho][FilipeGH] | [Geovane Freitas][GeovaneGH] | |

[DiegoGH]: https://github.com/DiegoCarlito
[FilipeGH]: https://github.com/Filipe-002
[GenilsonGH]: https://github.com/GenilsonJrs
[GeovaneGH]: https://github.com/GeovaneSFT
[GuilhermeGH]: https://github.com/Guilermanoo
[GustavoGH]: https://github.com/gustaallves
[JoãoVitorGH]: https://github.com/Joa0v
[MarcosGH]: https://github.com/Marcosatc147
[NicollasGH]: https://github.com/Nicollaxs
[Pedro Henrique]: https://github.com/PedroHhenriq
[SamuelGH]: https://github.com/SamuelRicosta