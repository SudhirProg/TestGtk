project('TestGtk', 'c')
gtkdep = dependency('gtk+-3.0 gmodule-2.0')
src = ['TestGtk.c']
exe = executable('TestGtk', sources : src, dependencies : gtkdep, link_args : '-Wl,--export-all-symbols'                                                                    )
