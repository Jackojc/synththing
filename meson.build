project('synththing', 'cpp',
	default_options: [
		'cpp_std=c++17',
		'cpp_rtti=false',
		'buildtype=debugoptimized',
		'default_library=static',
		'strip=true',
		'warning_level=2'
	],
	license: 'MPL-2.0'
)

sdl_dep = dependency('SDL2')
rtmidi_dep = dependency('rtmidi')

exe = executable('synththing', 'src/main.cpp',
	dependencies: [sdl_dep, rtmidi_dep],
	native: true
)

