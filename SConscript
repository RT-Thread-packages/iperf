from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c') + Glob('*.cpp')
CPPPATH = [cwd]

group = DefineGroup('iperf', src, depend = ['RT_USING_LWIP', 'PKG_USING_IPERF'], CPPPATH = CPPPATH)

Return('group')
