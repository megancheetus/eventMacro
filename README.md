# OpenKore - Macros para Up Completo (Em desenvolvimento)

Este arquivo `eventMacros.txt` contém um conjunto de macros para automação de up e tarefas de um personagem Justiceiro (Gunslinger) e sua evolução, Insurgente (Rebellion), no OpenKore. O objetivo é automatizar a jornada do nível 1 ao 99 e além, incluindo configuração de build, gerenciamento de suprimentos e execução de quests.

## Funcionalidades

* [cite_start]**Rota de Up Automática:** O bot atualiza o mapa de caça (`lockMap`) automaticamente com base no nível do personagem[cite: 2, 3, 18].
* **Build Automatizada:**
    * [cite_start]Distribui pontos de status (stats) conforme o personagem evolui[cite: 22, 23].
    * [cite_start]Aprende as habilidades (skills) de Justiceiro e Insurgente de forma automática[cite: 13].
* **Gerenciamento de Suprimentos:**
    * [cite_start]Define o uso e a compra de poções, com valores mínimos de zeny para realizar a compra[cite: 7, 8].
    * [cite_start]Prioriza o uso de poções de evento, como a "[Evento] Poção de Aprendiz", caso existam no inventário[cite: 35, 36].
* **Logística Automatizada:**
    * [cite_start]Retorna à cidade salva para vender itens quando o peso atinge o limite configurado (padrão 70%)[cite: 40].
    * [cite_start]Encontra automaticamente o NPC de utilidades na cidade para compra e venda[cite: 9, 10, 11].
* **Envio por RODEX:**
    * [cite_start]Envia automaticamente 100.000 zeny para um personagem principal quando o saldo ultrapassa 110.000[cite: 24, 25, 26, 27].
    * [cite_start]Envia automaticamente as cartas obtidas para um personagem principal[cite: 28, 30, 31].
* **Automação de Itens:**
    * [cite_start]Abre as "Caixas de Jornada" nos níveis correspondentes (1, 10, 20, etc.) [cite: 43, 44][cite_start], pulando a abertura se o peso estiver alto[cite: 45].
* **Automação de Quests:**
    * [cite_start]Executa a sequência de missões do Grupo do Éden para o nível 26-40 (Instrutora Boya), incluindo as caçadas de Skeletons e Poporings[cite: 49, 50, 52, 54, 55].
    * [cite_start]Coleta as recompensas, incluindo os equipamentos do Éden[cite: 57].
* **Segurança:**
    * [cite_start]Possui uma macro de fuga que detecta mapas perigosos (risco de sequestro) e utiliza um item de teleporte para sair do local[cite: 46, 47, 48].

## Instalação

1.  Faça uma cópia de segurança do seu `macros.txt` ou `eventMacros.txt` existente.
2.  Renomeie este arquivo para `eventMacros.txt`.
3.  Coloque o arquivo na pasta `control` do seu OpenKore.
4.  Certifique-se de que o `eventMacros` está ativado no seu `config.txt` (`eventMacros_load eventMacros.txt`).
5.  Configure um `rodexReceiver` no seu `config.txt` para que o envio de zeny e cartas funcione.

## Forks:
[cite_start]O modelo base das macros foi desenvolvido por **Teozord**[cite: 1].
