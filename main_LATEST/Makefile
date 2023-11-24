default_target: all
.PHONY : default_target

.NOTPARALLEL:

.SUFFIXES:

% : %,v

% : RCS/%

% : RCS/%,v

% : SCCS/s.%

% : s.%

.SUFFIXES: .hpux_make_needs_suffix_list

CC                   = g++
CXX_DEFINES          = 
CMAKE_BINARY_DIR     = .
CMAKE_SOURCE_DIR     = .
CXX_FLAGS            = -g -std=c++2a -std=gnu++20 -Wall -Werror -Wextra -pedantic -Wuninitialized
LDD_FLAGS            = $(CXX_FLAGS)
CXX_SOURCES          = $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ProjectCfg/Cfg.cpp                \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ProjectConst/Const.cpp            \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabCanIf/EcuabCanIf.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCanNm/ServiceCanNm.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCanSm/ServiceCanSm.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabCanTp/EcuabCanTp.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabCryIf/EcuabCryIf.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabEa/EcuabEa.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabEthIf/EcuabEthIf.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabFee/EcuabFee.cpp             \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabFrIf/EcuabFrIf.cpp           \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabFrTp/EcuabFrTp.cpp           \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabJ1939Tp/EcuabJ1939Tp.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabLinIf/EcuabLinIf.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabLinTp/EcuabLinTp.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabMemIf/EcuabMemIf.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabWdgIf/EcuabWdgIf.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalAdc/McalAdc.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalCan/McalCan.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalCry/McalCry.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalDio/McalDio.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalEep/McalEep.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalEth/McalEth.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalFls/McalFls.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalFr/McalFr.cpp                 \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalGpt/McalGpt.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalIcu/McalIcu.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalLin/McalLin.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalMcu/McalMcu.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalOcu/McalOcu.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalPort/McalPort.cpp             \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalPwm/McalPwm.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalSpi/McalSpi.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalWdg/McalWdg.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceBswM/ServiceBswM.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCom/ServiceCom.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceComM/ServiceComM.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCsm/ServiceCsm.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDcm/ServiceDcm.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDem/ServiceDem.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDet/ServiceDet.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDlt/ServiceDlt.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceEcuM/ServiceEcuM.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceFiM/ServiceFiM.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ReSimFm/ReSimFm.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceFrNm/ServiceFrNm.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceIpduM/ServiceIpduM.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceNm/ServiceNm.cpp           \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceNvM/ServiceNvM.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceOs/ServiceOs.cpp           \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServicePduR/ServicePduR.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSchM/ServiceSchM.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSecOC/ServiceSecOC.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSokFm/ServiceSokFm.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceStartUp/ServiceStartUp.cpp \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceStbM/ServiceStbM.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceVkms/ServiceVkms.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceWdgM/ServiceWdgM.cpp       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ProjectARA/ProjectARA.cpp         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSwcEcuM/ServiceSwcEcuM.cpp \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSwcOs/ServiceSwcOs.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ApplSwcFoc/ApplSwcFoc.cpp         \

CXX_OBJECTS          = $(CMAKE_BINARY_DIR)/Cfg.o                               \
                       $(CMAKE_BINARY_DIR)/Const.o                             \
                       $(CMAKE_BINARY_DIR)/EcuabCanIf.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceCanNm.o                      \
                       $(CMAKE_BINARY_DIR)/ServiceCanSm.o                      \
                       $(CMAKE_BINARY_DIR)/EcuabCanTp.o                        \
                       $(CMAKE_BINARY_DIR)/EcuabCryIf.o                        \
                       $(CMAKE_BINARY_DIR)/EcuabEa.o                           \
                       $(CMAKE_BINARY_DIR)/EcuabEthIf.o                        \
                       $(CMAKE_BINARY_DIR)/EcuabFee.o                          \
                       $(CMAKE_BINARY_DIR)/EcuabFrIf.o                         \
                       $(CMAKE_BINARY_DIR)/EcuabFrTp.o                         \
                       $(CMAKE_BINARY_DIR)/EcuabJ1939Tp.o                      \
                       $(CMAKE_BINARY_DIR)/EcuabLinIf.o                        \
                       $(CMAKE_BINARY_DIR)/EcuabLinTp.o                        \
                       $(CMAKE_BINARY_DIR)/EcuabMemIf.o                        \
                       $(CMAKE_BINARY_DIR)/EcuabWdgIf.o                        \
                       $(CMAKE_BINARY_DIR)/McalAdc.o                           \
                       $(CMAKE_BINARY_DIR)/McalCan.o                           \
                       $(CMAKE_BINARY_DIR)/McalCry.o                           \
                       $(CMAKE_BINARY_DIR)/McalDio.o                           \
                       $(CMAKE_BINARY_DIR)/McalEep.o                           \
                       $(CMAKE_BINARY_DIR)/McalEth.o                           \
                       $(CMAKE_BINARY_DIR)/McalFls.o                           \
                       $(CMAKE_BINARY_DIR)/McalFr.o                            \
                       $(CMAKE_BINARY_DIR)/McalGpt.o                           \
                       $(CMAKE_BINARY_DIR)/McalIcu.o                           \
                       $(CMAKE_BINARY_DIR)/McalLin.o                           \
                       $(CMAKE_BINARY_DIR)/McalMcu.o                           \
                       $(CMAKE_BINARY_DIR)/McalOcu.o                           \
                       $(CMAKE_BINARY_DIR)/McalPort.o                          \
                       $(CMAKE_BINARY_DIR)/McalPwm.o                           \
                       $(CMAKE_BINARY_DIR)/McalSpi.o                           \
                       $(CMAKE_BINARY_DIR)/McalWdg.o                           \
                       $(CMAKE_BINARY_DIR)/ServiceBswM.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceCom.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceComM.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceCsm.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceDcm.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceDem.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceDet.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceDlt.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceEcuM.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceFiM.o                        \
                       $(CMAKE_BINARY_DIR)/ReSimFm.o                           \
                       $(CMAKE_BINARY_DIR)/ServiceFrNm.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceIpduM.o                      \
                       $(CMAKE_BINARY_DIR)/ServiceNm.o                         \
                       $(CMAKE_BINARY_DIR)/ServiceNvM.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceOs.o                         \
                       $(CMAKE_BINARY_DIR)/ServicePduR.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceSchM.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceSecOC.o                      \
                       $(CMAKE_BINARY_DIR)/ServiceSokFm.o                      \
                       $(CMAKE_BINARY_DIR)/ServiceStartUp.o                    \
                       $(CMAKE_BINARY_DIR)/ServiceStbM.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceVkms.o                       \
                       $(CMAKE_BINARY_DIR)/ServiceWdgM.o                       \
                       $(CMAKE_BINARY_DIR)/ProjectARA.o                        \
                       $(CMAKE_BINARY_DIR)/ServiceSwcEcuM.o                    \
                       $(CMAKE_BINARY_DIR)/ServiceSwcOs.o                      \
                       $(CMAKE_BINARY_DIR)/ApplSwcFoc.o                        \

CXX_INCLUDES         = -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_common             \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ProjectCompiler    \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ProjectCfg         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ProjectConst       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabCanIf         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCanNm       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCanSm       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabCanTp         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabCryIf         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabEa            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabEthIf         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabFee           \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabFrIf          \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabFrTp          \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabJ1939Tp       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabLinIf         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabLinTp         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabMemIf         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuabWdgIf         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalAdc            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalCan            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalCry            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalDio            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalEep            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalEth            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalFls            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalFr             \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalGpt            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalIcu            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalLin            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalMcu            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalOcu            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalPort           \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalPwm            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalSpi            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_McalWdg            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceBswM        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCom         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceComM        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceCsm         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDcm         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDem         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDet         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceDlt         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceEcuM        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceFiM         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ReSimFm            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceFrNm        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceIpduM       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceNm          \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceNvM         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceOs          \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServicePduR        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSchM        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSecOC       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSokFm       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceStartUp     \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceStbM        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceVkms        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceWdgM        \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ProjectARA         \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSwcEcuM     \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ServiceSwcOs       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ApplSwcFoc         \

CXX_OBJECTS1 = $(subst .cpp,.o,$(CXX_SOURCES))

all: Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe
.PHONY : all

clean:
	rm $(CMAKE_BINARY_DIR)/Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe  $(CXX_OBJECTS)
.PHONY : clean

%.o: %.cpp
	$(CC) $(CXX_FLAGS) $(CXX_INCLUDES) -c $<

Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe: $(CXX_OBJECTS1)
	$(CC) $(LDD_FLAGS) -o $(CMAKE_BINARY_DIR)/Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe $(CXX_OBJECTS)
