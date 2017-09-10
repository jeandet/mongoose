project('mongoose', 'c')

mongoose_lib = library('mongoose',
                       'mongoose.c',
                       install : true
                       )

inc = include_directories('.')

mongoose = declare_dependency(link_with : mongoose_lib,
                              include_directories : inc)

