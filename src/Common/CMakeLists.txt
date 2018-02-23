
set(SOURCES
    ${CMAKE_CURRENT_LIST_DIR}/WorkingBuffer.h
    ${CMAKE_CURRENT_LIST_DIR}/AtomicOps.h
    ${CMAKE_CURRENT_LIST_DIR}/AtomicPointer.h
    ${CMAKE_CURRENT_LIST_DIR}/Version.h
    ${CMAKE_CURRENT_LIST_DIR}/Decimal.h
    ${CMAKE_CURRENT_LIST_DIR}/Constants.h
    ${CMAKE_CURRENT_LIST_DIR}/Exceptions.h
    ${CMAKE_CURRENT_LIST_DIR}/Decimal.cpp
    ${CMAKE_CURRENT_LIST_DIR}/Logger.h
    ${CMAKE_CURRENT_LIST_DIR}/QuickFASTPch.h
    ${CMAKE_CURRENT_LIST_DIR}/Value_fwd.h
    ${CMAKE_CURRENT_LIST_DIR}/BitMap.cpp
    ${CMAKE_CURRENT_LIST_DIR}/Profiler.cpp
    ${CMAKE_CURRENT_LIST_DIR}/WorkingBuffer.cpp
    ${CMAKE_CURRENT_LIST_DIR}/QuickFAST_Export.h
    ${CMAKE_CURRENT_LIST_DIR}/QuickFASTPch.cpp
    ${CMAKE_CURRENT_LIST_DIR}/Logger_fwd.h
    ${CMAKE_CURRENT_LIST_DIR}/dllmain.cpp
    ${CMAKE_CURRENT_LIST_DIR}/ByteSwapper.h
    ${CMAKE_CURRENT_LIST_DIR}/BitMap.h
    ${CMAKE_CURRENT_LIST_DIR}/AtomicCounter.h
    ${CMAKE_CURRENT_LIST_DIR}/Types.h
    ${CMAKE_CURRENT_LIST_DIR}/Profiler.h
    ${CMAKE_CURRENT_LIST_DIR}/StringBuffer.h
    ${CMAKE_CURRENT_LIST_DIR}/Decimal_fwd.h
    ${CMAKE_CURRENT_LIST_DIR}/Value.h
    ${CMAKE_CURRENT_LIST_DIR}/Types.cpp
    )

target_sources(QuickFAST PRIVATE ${SOURCES})
