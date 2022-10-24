cmake_minimum_required(VERSION 3.23.2)

project(
   Windows_uVisionV5p37_BldcFocSensorlessTLE9879QXA40_R2021
   VERSION 0.1
)

SET(CMAKE_CXX_STANDARD 20)
SET(CMAKE_CXX_STANDARD_REQUIRED True)

add_definitions(
   -g
   -std=c++2a
   -Wall
   -Werror
   -Wextra
   -pedantic
   -Wuninitialized
)

add_executable(
   Windows_uVisionV5p37_BldcFocSensorlessTLE9879QXA40_R2021
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_ApplSwcFoc/ApplSwcFoc.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_ApplSwcFoc/ApplSwcFoc_Pbcfg.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_common/Mat.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceStartUp/ServiceStartUp.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceNvM/Table.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceWdgM/mon.cpp

   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_CddBdrv/bdrv.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalAdc/adc1.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalAdc/adc2.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalAdc/csa.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalGpt/ccu6.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalGpt/gpt12e.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalGpt/scu.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalLin/lin.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalMcu/int.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalMcu/pmu.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalMcu/sfr_access.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalMcu/tle_device.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalPort/port.cpp
   ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalWdg/wdt1.cpp

#  ${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalMcu/isr.cpp
#  ${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceStartUp/bootrom.cpp
#  ${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceStartUp/system_tle987x.cpp
)

target_include_directories(
   Windows_uVisionV5p37_BldcFocSensorlessTLE9879QXA40_R2021 PUBLIC
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_ApplSwcFoc"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_common"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_ProjectARA"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceNvM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceStartUp"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_ServiceWdgM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_CddBdrv"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalAdc"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalGpt"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalLin"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalMcu"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalPort"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_McalWdg"
)

