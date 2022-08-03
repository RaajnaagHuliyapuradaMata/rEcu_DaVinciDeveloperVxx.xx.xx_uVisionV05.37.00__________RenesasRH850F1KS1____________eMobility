cmake_minimum_required(VERSION 3.23.2)

project(
   Windows10Home_uVisionV5p37_PEAQc150_BldcFocSensorless_TLE9879QXA40
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
   Windows10Home_uVisionV5p37_PEAQc150_BldcFocSensorless_TLE9879QXA40
   source/SmbLnk2_CfgGen/CfgGen.cpp
   source/SmbLnk2_Const/Const.cpp
   source/SmbLnk2_Fee/Fee.cpp
   source/SmbLnk2_MemIf/MemIf.cpp
   source/SmbLnk2_Adc/Adc.cpp
   source/SmbLnk2_Dio/Dio.cpp
   source/SmbLnk2_Fls/Fls.cpp
   source/SmbLnk2_Gpt/Gpt.cpp
   source/SmbLnk2_Icu/Icu.cpp
   source/SmbLnk2_Mcu/Mcu.cpp
   source/SmbLnk2_Ocu/Ocu.cpp
   source/SmbLnk2_Port/Port.cpp
   source/SmbLnk2_Pwm/Pwm.cpp
   source/SmbLnk2_Spi/Spi.cpp
   source/SmbLnk2_BswM/BswM.cpp
   source/SmbLnk2_Dcm/Dcm.cpp
   source/SmbLnk2_Dem/Dem.cpp
   source/SmbLnk2_Det/Det.cpp
   source/SmbLnk2_Dlt/Dlt.cpp
   source/SmbLnk2_EcuM/EcuM.cpp
   source/SmbLnk2_FiM/FiM.cpp
   source/SmbLnk2_Fm/Fm.cpp
   source/SmbLnk2_NvM/NvM.cpp
   source/SmbLnk2_Os/Os.cpp
   source/SmbLnk2_SchM/SchM.cpp
   source/SmbLnk2_StartUp/StartUp.cpp
   source/SmbLnk2_Rte/Rte.cpp
   source/SmbLnk2_SwcServiceEcuM/SwcServiceEcuM.cpp
   source/SmbLnk2_SwcServiceOs/SwcServiceOs.cpp
   source/SmbLnk2_SwcApplFoc/SwcApplFoc.cpp
)

target_include_directories(
   Windows10Home_uVisionV5p37_PEAQc150_BldcFocSensorless_TLE9879QXA40 PUBLIC
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_common"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Compiler"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_CfgGen"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Const"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Fee"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_MemIf"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Adc"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Dio"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Fls"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Gpt"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Icu"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Mcu"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Ocu"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Port"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Pwm"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Spi"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_BswM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Dcm"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Dem"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Det"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Dlt"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_EcuM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_FiM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Fm"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_NvM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Os"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_SchM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_StartUp"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_Rte"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_SwcServiceEcuM"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_SwcServiceOs"
   "${PROJECT_SOURCE_DIR}/source/SmbLnk2_SwcApplFoc"
)

