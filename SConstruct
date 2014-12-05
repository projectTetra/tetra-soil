env = Environment()
env['CPPPATH'] = [ './src' ];
env['LIBPATH'] = [];
env['LIBS'] = [];

env['CC'] = 'clang';

buildLib = env.Library('./bin/tetraSoil', Glob('src/*.c'));

Default(buildLib);
