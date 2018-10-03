project(
    'Dyno', 'cpp',
    license: 'Boost',
    version: '0.0.1',
    default_options: [
        'cpp_std=c++17',
    ],
)

dyno_inc = include_directories('include')

boost_dep = dependency('boost', version: '>=1.66')

dyno_dep = declare_dependency(
    include_directories: dyno_inc,
    dependencies: boost_dep
)
