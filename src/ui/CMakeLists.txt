list(APPEND GAME_SOURCES
	"${CMAKE_CURRENT_SOURCE_DIR}/Button.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Field.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Font.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Frame.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Image.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Slider.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Text.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Widget.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/GameUI.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/LoadingScreen.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/MainMenu.cpp"
)
list(APPEND EDITOR_SOURCES
	"${CMAKE_CURRENT_SOURCE_DIR}/Button.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Field.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Font.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Frame.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Image.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Slider.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Text.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/Widget.cpp"
	"${CMAKE_CURRENT_SOURCE_DIR}/LoadingScreen.cpp"
)

set(GAME_SOURCES ${GAME_SOURCES} PARENT_SCOPE)
set(EDITOR_SOURCES ${EDITOR_SOURCES} PARENT_SCOPE)
