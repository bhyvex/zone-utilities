CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

ADD_SUBDIRECTORY(bullet)

IF(EQEMU_ENABLE_GL)
	ADD_SUBDIRECTORY(glew)
	ADD_SUBDIRECTORY(glfw)
	ADD_SUBDIRECTORY(imgui)
	ADD_SUBDIRECTORY(recast)
ENDIF(EQEMU_ENABLE_GL)
