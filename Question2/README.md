# Question 2

## Objective

Create child processes using `fork()`, monitor them, prevent zombie processes, and terminate an unresponsive child using signals.

## Commands

```bash
gcc process_manager.c -o process_manager
./process_manager
```

## Explanation

- `fork()` creates child processes.
- `waitpid()` waits for child processes and prevents zombie processes.
- `kill()` with `SIGKILL` terminates an unresponsive child process.

## Files

- process_manager.c
- output.txt
