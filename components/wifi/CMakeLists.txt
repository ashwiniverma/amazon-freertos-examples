# include paths of this components.
set(COMPONENT_ADD_INCLUDEDIRS include)

# Add a dependency on the common component to the wifi component
set(COMPONENT_REQUIRES common)

# add this components, this will define a CMake library target.
register_component()
