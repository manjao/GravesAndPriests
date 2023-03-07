# Set the name of the executable target
set(EXECUTABLE_NAME grave)

# Set the source files for the executable target
set(EXECUTABLE_SOURCES
    main.cpp
)

# Create the executable target
add_executable(${EXECUTABLE_NAME} ${EXECUTABLE_SOURCES})

include_directories(../include)
