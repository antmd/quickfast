
find_package(Boost MODULE REQUIRED COMPONENTS date_time filesystem system thread)
find_package(XercesC MODULE REQUIRED)
add_library(QuickFAST "")
add_library(OCI::QuickFAST ALIAS QuickFAST)

include(Application/CMakeLists.txt)
include(Codecs/CMakeLists.txt)
include(Common/CMakeLists.txt)
include(Communication/CMakeLists.txt)
include(Messages/CMakeLists.txt)

target_link_libraries(QuickFAST
    PUBLIC
        Boost::filesystem
        Boost::system
        Boost::thread
        XercesC::XercesC
    )

target_include_directories(QuickFAST
    PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)
