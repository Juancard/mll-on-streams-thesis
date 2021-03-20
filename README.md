# mll-on-streams-thesis

# Install OS dependencies
```bat
xargs sudo apt install < requirements_os.txt
```

# Download dictionary files
```bat
sudo wget http://ftp.vim.org/vim/runtime/spell/es.utf-8.spl -P /usr/share/vim/vim82/spell/
sudo wget http://ftp.vim.org/vim/runtime/spell/es.utf-8.sug -P /usr/share/vim/vim82/spell/
sudo wget http://ftp.vim.org/vim/runtime/spell/es.latin1.spl -P /usr/share/vim/vim82/spell/
sudo wget http://ftp.vim.org/vim/runtime/spell/es.latin1.sug -P /usr/share/vim/vim82/spell/

```

## Useful commands
- Update glossary:
```bat
makeglossaries tesis
```

- Update bibliography
```bat
biber tesis
```

- Run spell and grammar checks:
```bat
textidote > report_textidote.html
```
