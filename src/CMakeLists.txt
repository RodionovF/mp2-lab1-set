set(target ${MP2_LIBRARY})

s

file(GLOB hdrs "*.h*" "${MP2_INCLUDEû}/*.h*")
file(GLOB srcs "*.cpp")

add_library(${target} STATIC ${srcs} ${hdrs})
target_link_libraries(${target} ${LIBRARY_DEPS})
