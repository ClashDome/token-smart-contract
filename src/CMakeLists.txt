project(clashdometkn)

set(EOSIO_WASM_OLD_BEHAVIOR "Off")
find_package(eosio.cdt)

add_contract( clashdometkn clashdometkn eosio.token.cpp )
target_include_directories( clashdometkn PUBLIC ${CMAKE_SOURCE_DIR}/../include )
target_ricardian_directory( clashdometkn ${CMAKE_SOURCE_DIR}/../ricardian )