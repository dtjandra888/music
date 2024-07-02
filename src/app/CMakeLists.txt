

qt_add_executable(music-player
    MainWidget.cpp
    MainWidget.h
    main.cpp
)

target_link_libraries(music-player PRIVATE Qt6::Widgets)

set_target_properties(music-player PROPERTIES OUTPUT_NAME wip)
