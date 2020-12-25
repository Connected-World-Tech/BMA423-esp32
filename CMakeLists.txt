
set(COMPONENT_SRC_DIR BMA423-Sensor-API)
file(GLOB_RECURSE SOURCES ${BMA423-Sensor-API}/*.c)

idf_component_register(SRCS ${SOURCES}
                       INCLUDE_DIRS ${BMA423-Sensor-API}
                       )

