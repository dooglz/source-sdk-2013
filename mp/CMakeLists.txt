add_library(sdk_mp_hl2_client SHARED "${CMAKE_CURRENT_SOURCE_DIR}/src/game/client/cdll_client_int.cpp")
add_library(sdk_mp_hl2_server SHARED "${CMAKE_CURRENT_SOURCE_DIR}/src/game/server/game.cpp")
add_library(sdk_mp_episodic_client SHARED "${CMAKE_CURRENT_SOURCE_DIR}/src/game/client/cdll_client_int.cpp")
add_library(sdk_mp_episodic_server SHARED "${CMAKE_CURRENT_SOURCE_DIR}/src/game/server/game.cpp")