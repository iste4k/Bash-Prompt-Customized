# Bash Prompt Customization

Open terminal: `Ctrl` + `Alt` + `T`

Type on terminal:

```bash
sudo apt update && sudo apt upgrade
```

After that,

```bash
sudo nano ~/.bashrc
```

After opening `.bashrc` file in nano editor, go to the last line of the file.

Then write:

```bash
export PS1="\e[1;32m[\t] $ \e[0m"
```

in the last new line.

Then, `Ctrl` + `o`. After that, `Ctrl` + `x` to save the file.