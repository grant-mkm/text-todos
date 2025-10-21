# text-todos
Simple text file driven todo list

## Installation

Save .todos to your ~/ home directory.

Add `source ~/.todos` to your ~/.zshrc

Run `source ~/.zshrc` to load the file and enable the `todo` command

## Text file example

```
todo get milk
done walk the dog
```

## Example todo output

```
> todo

1 get milk
2 walk the dog
```

## Commands

### Toggle todo

todo done 1

Will mark "get milk" as done

```
done get milk
done walk the dog
```

todo done 1

Will reset "get milk" back to a todo

```
todo get milk
done walk the dog
```
