datadocs = files('cygport.conf', 'mirrors')

install_data('mirrors',
             'sample.cygport',
             install_dir: pkgdatadir)

install_data('gnuconfig/config.guess',
             'gnuconfig/config.sub',
             install_dir: pkgdatadir,
             install_mode: 'rwxr-xr-x')

install_data('cygport.xml',
             install_dir: join_paths(datadir, 'mime', 'packages'))

install_data('cygport.nanorc',
             install_dir: join_paths(datadir, 'nano'))

install_data('cygport.vim',
             install_dir: join_paths(datadir, 'vim', 'vimfiles', 'ftdetect'))

install_data('cygport-bash-completion',
             install_dir: join_paths(sysconfdir, 'bash_completion.d'))

install_data('cygport-xvfb.conf',
             install_dir: join_paths(sysconfdir, 'X11'))

