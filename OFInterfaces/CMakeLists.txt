IF(OF_PYTHON_MODULE)
  INSTALL(FILES
    ${CMAKE_CURRENT_SOURCE_DIR}/PyQtOF.py
    ${CMAKE_CURRENT_SOURCE_DIR}/PyQtOFInterfaceC.py
    DESTINATION ${OF_INTERFACE_DIR}
  )
ENDIF()
