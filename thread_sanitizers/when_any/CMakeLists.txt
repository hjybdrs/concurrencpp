cmake_minimum_required(VERSION 3.16)
project(when_any_test)

add_executable(
	when_any_test
	main.cpp
	)

target_link_libraries(when_any_test concurrencpp)
