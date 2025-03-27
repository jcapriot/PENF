penf_srcs = [
    'penf.F90',
    'penf_allocatable_memory.F90',
    'penf_b_size.F90',
    'penf_global_parameters_variables.F90',
    'penf_stringify.F90',
]

# penf_include_dir = include_directories('.')


lib_penf = library(
    'penf',
    penf_srcs,
)

penf_dep = declare_dependency(
        # include_directories: penf_include_dir,
        link_with: lib_penf,
)