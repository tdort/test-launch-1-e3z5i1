include $(THEOS)/makefiles/common.mk

LIBRARY_NAME = EnterpriseLoader

EnterpriseLoader_FILES = \
    EnterpriseLoader.m \
    ../src/Utils.m \
    ../src/EnterpriseCompare.m \
    $(wildcard ../src/LCUtils/*.m)

EnterpriseLoader_CFLAGS = -fobjc-arc
EnterpriseLoader_LIBRARIES = archive
EnterpriseLoader_INSTALL_PATH = /Applications/Geode.app/Frameworks

include $(THEOS_MAKE_PATH)/library.mk
