FILE(GLOB HTML_FILES *.htm)
FILE(GLOB I18N_FILES i18n/*.properties)
FILE(GLOB JS_FILES js/*.js)

INSTALL(FILES ${HTML_FILES} DESTINATION ${QGIS_DATA_DIR}/python/console/console_help)
INSTALL(FILES ${I18N_FILES} DESTINATION ${QGIS_DATA_DIR}/python/console/console_help/i18n)
INSTALL(FILES ${JS_FILES} DESTINATION ${QGIS_DATA_DIR}/python/console/console_help/js)
