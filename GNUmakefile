#
# GNUmakefile - Generated by ProjectCenter
#
ifeq ($(GNUSTEP_MAKEFILES),)
 GNUSTEP_MAKEFILES := $(shell gnustep-config --variable=GNUSTEP_MAKEFILES 2>/dev/null)
endif
ifeq ($(GNUSTEP_MAKEFILES),)
 $(error You need to set GNUSTEP_MAKEFILES before compiling!)
endif

include $(GNUSTEP_MAKEFILES)/common.make

#
# Framework
#
VERSION = 0.1
PACKAGE_NAME = XCode
FRAMEWORK_NAME = XCode

#
# Resource files
#
XCode_RESOURCE_FILES = \
Resources/Version \

#
# Header files
#
XCode_HEADER_FILES = \
PBXBuildFile.h \
PBXCoder.h \
PBXCommon.h \
PBXContainer.h \
PBXContainerItemProxy.h \
PBXFileReference.h \
PBXFrameworksBuildPhase.h \
PBXGroup.h \
PBXHeadersBuildPhase.h \
PBXNativeTarget.h \
PBXProject.h \
PBXReferenceProxy.h \
PBXResourcesBuildPhase.h \
PBXShellScriptBuildPhase.h \
PBXSourcesBuildPhase.h \
PBXTargetDependency.h \
PBXVariantGroup.h \
XCBuildConfiguration.h \
XCConfigurationList.h

#
# Class files
#
XCode_OBJC_FILES = \
PBXBuildFile.m \
PBXCoder.m \
PBXCommon.m \
PBXContainerItemProxy.m \
PBXContainer.m \
PBXFileReference.m \
PBXFrameworksBuildPhase.m \
PBXGroup.m \
PBXHeadersBuildPhase.m \
PBXNativeTarget.m \
PBXProject.m \
PBXReferenceProxy.m \
PBXResourcesBuildPhase.m \
PBXShellScriptBuildPhase.m \
PBXSourcesBuildPhase.m \
PBXTargetDependency.m \
PBXVariantGroup.m \
XCBuildConfiguration.m \
XCConfigurationList.m

#
# Makefiles
#
-include GNUmakefile.preamble
include $(GNUSTEP_MAKEFILES)/aggregate.make
include $(GNUSTEP_MAKEFILES)/framework.make
-include GNUmakefile.postamble
