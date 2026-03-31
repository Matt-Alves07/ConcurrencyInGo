# ConcurrencyInGo

Repositório de exemplos e projetos em Go focados em concorrência, canais, mutexes e padrões de sincronização.

## Estrutura do repositório

- `01.FirstExample/`: exemplo inicial de goroutines e comunicação básica.
- `02.WaitGroups/`: uso de `sync.WaitGroup` para sincronizar goroutines.
- `03.TestingGoRoutines/first-example/`: testes e código para goroutines em Go.
- `04.Challenge01/challenge-1/`: desafio sobre controle de concorrência e sincronização.
- `05.RaceConditions/`: demonstração de condição de corrida e como detectar/evitar.
- `06.Mutex/`: exemplo de uso de `sync.Mutex` para proteção de dados compartilhados.
- `07.WeeklyIncomeCalculator/`: calculadora de renda semanal com concorrência.
- `08.ProducerConsumerProblem.Channels/`: solução do problema produtor-consumidor com canais.
- `09.DiningProblem/`: problema dos filósofos jantando (Dining Philosophers) e testes relacionados.
- `10.SimpleChannels/`: manipulação básica de canais e sinais.
- `11.ChannelSelect/`: utilização de `select` para multiplexação de canais.
- `12.BufferedChannels/`: canais com buffer e efeitos no fluxo de dados.
- `13.SleepingBarber/`: implementação do problema do barbeiro dorminhoco.
- `14.FinalProject/`: aplicação completa com servidor web, modelo de dados, rotas, templates e testes.

## Como usar

Cada subdiretório contém um módulo Go independente (`go.mod`) ou uma subpasta de módulo.

1. Acesse o projeto desejado:
   - `cd 01.FirstExample`
   - `cd 02.WaitGroups`
   - etc.

2. Execute o exemplo ou teste:
   - `go run main.go` (quando houver)
   - `go test ./...` (para rodar testes)

## Links para acesso rápido

- [01.FirstExample](01.FirstExample/)
- [02.WaitGroups](02.WaitGroups/)
- [03.TestingGoRoutines/first-example](03.TestingGoRoutines/first-example/)
- [04.Challenge01/challenge-1](04.Challenge01/challenge-1/)
- [05.RaceConditions](05.RaceConditions/)
- [06.Mutex](06.Mutex/)
- [07.WeeklyIncomeCalculator](07.WeeklyIncomeCalculator/)
- [08.ProducerConsumerProblem.Channels](08.ProducerConsumerProblem.Channels/)
- [09.DiningProblem](09.DiningProblem/)
- [10.SimpleChannels](10.SimpleChannels/)
- [11.ChannelSelect](11.ChannelSelect/)
- [12.BufferedChannels](12.BufferedChannels/)
- [13.SleepingBarber](13.SleepingBarber/)
- [14.FinalProject](14.FinalProject/)

## Observações

- O projeto `14.FinalProject` contém app web com bancos de dados, Docker Compose e testes mais completos.
- Para cada exemplo, recomenda-se inspecionar o `main.go` e arquivos de teste para entender o comportamento concorrente.
