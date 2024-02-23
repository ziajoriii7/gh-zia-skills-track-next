# taskwarrior

file in `.taskrc`
## most common commands

```zsh
task add <action of task> due:<day>
```
how to put by default in due:day to due:eod?
```zsh
task done <ID> <or multiple IDs>
```
```zsh
task list
```

```zsh
task list due:today
```
```zsh
task calendar
```
```zsh:
task <ID> modify due:eod
```


## not that common commands but useful
```zsh
task ghistory.daily
```

```zsh
task list
```

```zsh
task <ID> start:yesterday
```

```zsh
task active
```






- Delete recurring tasks
```zsh
task all +PARENT
```
```zsh 
task delete <ID> or <or multiple IDs>
```

## general

```zsh
task stats
```
### sources:
- [Using Dates Effectively - TaskWarrior](https://taskwarrior.org/docs/using_dates/)
- [How do you use due dates? - Reddit](https://www.reddit.com/r/taskwarrior/comments/etln4c/how_do_you_use_due_dates/https://www.reddit.com/r/taskwarrior/comments/etln4c/how_do_you_use_due_dates/)
- [dates in taskswarrior](https://www.google.com/search?q=dates+in+taskswarrior&rlz=1C1GCEA_enPE1078PE1078&oq=dates+in+taskswarrior&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIJCAEQIRgKGKABMgkIAhAhGAoYoAEyCQgDECEYChigAdIBCDQxOTRqMGoxqAIAsAIA&sourceid=chrome&ie=UTF-8)
