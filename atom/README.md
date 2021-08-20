#Setting
Just copy settings .csons into `~/.atom` dir

# Packages
To track installed packages as well, you will need to run:
`apm list --installed --bare > ~/.atom/package.list`

And add that file to Git also. To restore, use:
`apm install --packages-file ~/.atom/package.list`
