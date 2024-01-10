# kusion workspace create

Create a new workspace

### Synopsis

This command creates a workspace with specified name and configuration file, where the file must be in the YAML format.

```
kusion workspace create
```

### Examples

```
  # Create a new workspace
  kusion workspace create dev -f dev.yaml
```

### Options

```
  -f, --file string   the path of workspace configuration file
  -h, --help          help for create
```

### Options inherited from parent commands

```
      --profile string          Name of profile to capture. One of (none|cpu|heap|goroutine|threadcreate|block|mutex) (default "none")
      --profile-output string   Name of the file to write the profile to (default "profile.pprof")
```

### SEE ALSO

* [kusion workspace](kusion-workspace.md)	 - Workspace is a logical concept representing a target that stacks will be deployed to

###### Auto generated by spf13/cobra on 4-Jan-2024