proviamo a cambiare username 
# try 1) FUNZIONA
`git config alias.alexcommit "-c user.name='Alex Mazzoni' -c user.email='alex.mazzoni3@studio.unibo.it' commit"`

usage example = git alexcommit -m ...

# try 2) FUNZIONA
config --local user.email user.name
