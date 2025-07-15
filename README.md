# OpenKore - Macros para Up Completo (Em desenvolvimento)

Este arquivo `eventMacros.txt` contém um conjunto de macros para automação de up e tarefas de um personagem Justiceiro (Gunslinger) e sua evolução, Insurgente (Rebellion), no OpenKore. O objetivo é automatizar a jornada do nível 1 ao 99 e além, incluindo configuração de build, gerenciamento de suprimentos e execução de quests.

## Funcionalidades

**Rota de Up Automática:** O bot atualiza o mapa de caça (`lockMap`) automaticamente com base no nível do personagem.
* **Build Automatizada:**
    * Distribui pontos de status (stats) conforme o personagem evolui.
    * Aprende as habilidades (skills) de Justiceiro e Insurgente de forma automática.
* **Gerenciamento de Suprimentos:**
    * Define o uso e a compra de poções, com valores mínimos de zeny para realizar a compra.
    * Prioriza o uso de poções de evento, como a "[Evento] Poção de Aprendiz", caso existam no inventário.
* **Logística Automatizada:**
    * Retorna à cidade salva para vender itens quando o peso atinge o limite configurado (padrão 70%).
    * Encontra automaticamente o NPC de utilidades na cidade para compra e venda.
* **Envio por RODEX:**
    * Envia automaticamente 100.000 zeny para um personagem principal quando o saldo ultrapassa 110.000.
    * Envia automaticamente as cartas obtidas para um personagem principal.
* **Automação de Itens:**
    * Abre as "Caixas de Jornada" nos níveis correspondentes (1, 10, 20, etc.) [cite: 43, 44][cite_start], pulando a abertura se o peso estiver alto.
* **Automação de Quests:**
    * Executa a sequência de missões do Grupo do Éden para o nível 26-40 (Instrutora Boya), incluindo as caçadas de Skeletons e Poporings.
    * Coleta as recompensas, incluindo os equipamentos do Éden.
* **Segurança:**
    * Possui uma macro de fuga que detecta mapas perigosos (risco de sequestro) e utiliza um item de teleporte para sair do local.

## Instalação

1.  Faça uma cópia de segurança do seu `macros.txt` ou `eventMacros.txt` existente.
2.  Renomeie este arquivo para `eventMacros.txt`.
3.  Coloque o arquivo na pasta `control` do seu OpenKore.
4.  Certifique-se de que o `eventMacros` está ativado no seu `config.txt` (`eventMacros_load eventMacros.txt`).
5.  Configure um `rodexReceiver` no seu `config.txt` para que o envio de zeny e cartas funcione.

## Forks:
O modelo base da macro dos mapas foi desenvolvido por **Teozord**.
