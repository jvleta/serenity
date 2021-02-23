set(SOURCES
    Card.cpp
    CardStack.cpp
    main.cpp
    SpiderWidget.cpp
)

serenity_app(Spider ICON app-solitaire)
target_link_libraries(Spider LibGUI LibGfx LibCore)
