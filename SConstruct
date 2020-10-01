import os
import scripts.app_helper as app

helper = app.Helper(ARGUMENTS)
helper.set_dll_def('src/vlabel.def').set_libs(['vlabel']).call(DefaultEnvironment)

SConscriptFiles = ['src/SConscript', 'demos/SConscript', 'tests/SConscript']
SConscript(SConscriptFiles)
