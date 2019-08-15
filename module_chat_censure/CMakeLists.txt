AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/ChatCensure.cpp")
AC_ADD_SCRIPT_LOADER("ChatCensure" "${CMAKE_CURRENT_LIST_DIR}/src/loader.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/my_customChatCensure.conf.dist")