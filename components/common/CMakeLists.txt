# include paths of this components.
set(COMPONENT_ADD_INCLUDEDIRS include)

# source files of this components.
set(COMPONENT_SRCDIRS src)

# Add a dependency on the bluetooth espressif component to the common component
set(COMPONENT_REQUIRES lwip)

# add this components, this will define a CMake library target.
register_component()
