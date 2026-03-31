# ConcurrencyInGo

Repository of Go examples and projects focused on concurrency, channels, mutexes, and synchronization patterns.

## Repository structure

- `01.FirstExample/`: initial example of goroutines and basic communication.
- `02.WaitGroups/`: using `sync.WaitGroup` to synchronize goroutines.
- `03.TestingGoRoutines/first-example/`: tests and code for goroutines in Go.
- `04.Challenge01/challenge-1/`: challenge exercise for concurrency control and synchronization.
- `05.RaceConditions/`: demonstration of race conditions and how to detect/avoid them.
- `06.Mutex/`: example using `sync.Mutex` for protecting shared data.
- `07.WeeklyIncomeCalculator/`: concurrent weekly income calculator.
- `08.ProducerConsumerProblem.Channels/`: producer-consumer problem solution using channels.
- `09.DiningProblem/`: dining philosophers problem with tests.
- `10.SimpleChannels/`: basic channel operations and signaling.
- `11.ChannelSelect/`: using `select` for channel multiplexing.
- `12.BufferedChannels/`: buffered channels and their effects on data flow.
- `13.SleepingBarber/`: sleeping barber problem implementation.
- `14.FinalProject/`: complete web application with data models, routes, templates, and tests.

## How to use

Each subdirectory contains an independent Go module (`go.mod`) or a submodule directory.

1. Navigate to the desired project:
   - `cd 01.FirstExample`
   - `cd 02.WaitGroups`
   - etc.

2. Run the example or tests:
   - `go run main.go` (when available)
   - `go test ./...` (to run tests)

## Quick access links

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

## Notes

- The `14.FinalProject` project includes a web app with database support, Docker Compose, and more extensive tests.
- For each example, review `main.go` and test files to understand the concurrent behavior.
