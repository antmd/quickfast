

set(SOURCES
    ${CMAKE_CURRENT_LIST_DIR}/DNDecoderConnectionImpl_fwd.h
    ${CMAKE_CURRENT_LIST_DIR}/CommandArgParser.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DecoderConnection.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DecoderConfiguration.h
    ${CMAKE_CURRENT_LIST_DIR}/CommandArgParser.h
    ${CMAKE_CURRENT_LIST_DIR}/DNDecoderConnectionImpl.h
    ${CMAKE_CURRENT_LIST_DIR}/DNDecoderConnectionImpl.cpp
    ${CMAKE_CURRENT_LIST_DIR}/DecoderConnection.h
    ${CMAKE_CURRENT_LIST_DIR}/CommandArgHandler.h
    ${CMAKE_CURRENT_LIST_DIR}/QuickFAST.h
    ${CMAKE_CURRENT_LIST_DIR}/DecoderConnection_fwd.h
    ${CMAKE_CURRENT_LIST_DIR}/DecoderConfiguration_fwd.h
    )

target_sources(QuickFAST PRIVATE ${SOURCES})
