project('libqpbo', 'cpp', version: '1.4.0')

sources = ['qpbo.cpp',
           'qpbo_extra.cpp',
           'qpbo_maxflow.cpp',
           'qpbo_postprocessing.cpp']

inc = include_directories('.')
libqpbo = static_library('qpbo', 
                    sources,
                    install: false)

libqpbo_dep = declare_dependency(include_directories: inc, link_with : libqpbo)