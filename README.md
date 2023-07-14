# go-cli-template
This is a template that can be used with GitHub Codespaces to get you up and running with your CLI project in minutes.

This project is using https://github.com/spf13/cobra as a foundation.

## Running out of the box
run the commands:

```bash
go buiild
./go-cli-template
```

## Commands

So far there is only 1 command created, `example` and this can be seen within the `/cmd` directory.

The pre-installed Cobra CLI tools can help make your project far more extensible with little work.

To see the commands available with Cobra, run the command: 

```bash
cobra-cli -h
```

### Adding a new command

Adding a new command at the root level is very easy to do, you just need to use the following command:

```bash
cobra-cli add <name of new command>
```

Once you have done this, navigate to the new command within the `/cmd` directory and edit the boilerplate code provided for your needs.

This is a basic foundation for you to build ontop of without the hassel of setup. Adding flags and subcommand palletes is bespoke to your own projet and information on how to do that can be found in the offical docs - https://pkg.go.dev/github.com/spf13/cobra#section-readme

