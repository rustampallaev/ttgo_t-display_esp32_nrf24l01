# Warning! This code was automatically generated for projects
# without default 'CMakeLists.txt' file.

set(app_sources
	"delay.c"
	"display.c"
	"main.c"
	"nrf24l01.c"
	"radio.c"
)

idf_component_register(SRCS ${app_sources})
