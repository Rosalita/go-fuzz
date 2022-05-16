# go-fuzz
Trying out the new fuzzing in Go 1.18

To run tests with fuzzing `go test -fuzz ./..`
Running go test again without the fuzz tag, the new failing seed corpus entry will be used.
