set(target web-prog)

add_executable(${target})

target_sources(
	${target}
	PRIVATE
	main.cpp
)

target_link_libraries(
	${target}
	
)
