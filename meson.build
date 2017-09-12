project('mongoose', 'c')

thread_dep = dependency('threads')
mongoose_lib = library('mongoose',
                       'mongoose.c',
                       dependencies : [thread_dep],
                       install : true
                       )

inc = include_directories('.')

mongoose = declare_dependency(link_with : mongoose_lib,
                              dependencies : [thread_dep],
                              include_directories : inc)

