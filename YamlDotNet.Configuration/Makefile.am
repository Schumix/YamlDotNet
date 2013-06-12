
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- -debug "-define:DEBUG;TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Debug/YamlDotNet.Configuration.dll
ASSEMBLY_MDB = $(ASSEMBLY).mdb
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll \
	../YamlDotNet.RepresentationModel/bin/Debug/YamlDotNet.RepresentationModel.dll
BUILD_DIR = bin/Debug/

YAMLDOTNET_CONFIGURATION_DLL_MDB_SOURCE=bin/Debug/YamlDotNet.Configuration.dll.mdb
YAMLDOTNET_CONFIGURATION_DLL_MDB=$(BUILD_DIR)/YamlDotNet.Configuration.dll.mdb
YAMLDOTNET_CORE_DLL_SOURCE=../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll
YAMLDOTNET_CORE_DLL_MDB_SOURCE=../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll.mdb
YAMLDOTNET_CORE_DLL_MDB=$(BUILD_DIR)/YamlDotNet.Core.dll.mdb
YAMLDOTNET_REPRESENTATIONMODEL_DLL_SOURCE=../YamlDotNet.RepresentationModel/bin/Debug/YamlDotNet.RepresentationModel.dll
YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB_SOURCE=../YamlDotNet.RepresentationModel/bin/Debug/YamlDotNet.RepresentationModel.dll.mdb
YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB=$(BUILD_DIR)/YamlDotNet.RepresentationModel.dll.mdb

endif

if ENABLE_RELEASE
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-define:TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Release/YamlDotNet.Configuration.dll
ASSEMBLY_MDB = 
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet.Core/bin/Release/YamlDotNet.Core.dll \
	../YamlDotNet.RepresentationModel/bin/Release/YamlDotNet.RepresentationModel.dll
BUILD_DIR = bin/Release/

YAMLDOTNET_CONFIGURATION_DLL_MDB=
YAMLDOTNET_CORE_DLL_SOURCE=../YamlDotNet.Core/bin/Release/YamlDotNet.Core.dll
YAMLDOTNET_CORE_DLL_MDB=
YAMLDOTNET_REPRESENTATIONMODEL_DLL_SOURCE=../YamlDotNet.RepresentationModel/bin/Release/YamlDotNet.RepresentationModel.dll
YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB=

endif

AL=al2
SATELLITE_ASSEMBLY_NAME=$(notdir $(basename $(ASSEMBLY))).resources.dll

PROGRAMFILES = \
	$(YAMLDOTNET_CONFIGURATION_DLL_MDB) \
	$(YAMLDOTNET_CORE_DLL) \
	$(YAMLDOTNET_CORE_DLL_MDB) \
	$(YAMLDOTNET_REPRESENTATIONMODEL_DLL) \
	$(YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB)  

LINUX_PKGCONFIG = \
	$(YAMLDOTNET_CONFIGURATION_PC)  


RESGEN=resgen2
	
all: $(ASSEMBLY) $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

FILES = \
	../CommonAssemblyInfo.cs \
	ConfigurationLoader.cs \
	DotNetConfigurationProvider.cs \
	IConfigurationProvider.cs \
	Properties/AssemblyInfo.cs \
	YamlConfigurationProvider.cs \
	YamlConfigurationSection.cs 

DATA_FILES = 

RESOURCES = 

EXTRAS = \
	../YamlDotNet.snk \
	yamldotnet.configuration.pc.in 

REFERENCES =  \
	System \
	System.Core \
	System.Data \
	System.Xml \
	System.Configuration

DLL_REFERENCES = 

CLEANFILES = $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

include $(top_srcdir)/Makefile.include

YAMLDOTNET_CORE_DLL = $(BUILD_DIR)/YamlDotNet.Core.dll
YAMLDOTNET_REPRESENTATIONMODEL_DLL = $(BUILD_DIR)/YamlDotNet.RepresentationModel.dll
YAMLDOTNET_CONFIGURATION_PC = $(BUILD_DIR)/yamldotnet.configuration.pc

$(eval $(call emit-deploy-target,YAMLDOTNET_CORE_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_CORE_DLL_MDB))
$(eval $(call emit-deploy-target,YAMLDOTNET_REPRESENTATIONMODEL_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB))
$(eval $(call emit-deploy-wrapper,YAMLDOTNET_CONFIGURATION_PC,yamldotnet.configuration.pc))


$(eval $(call emit_resgen_targets))
$(build_xamlg_list): %.xaml.g.cs: %.xaml
	xamlg '$<'

$(ASSEMBLY_MDB): $(ASSEMBLY)

$(ASSEMBLY): $(build_sources) $(build_resources) $(build_datafiles) $(DLL_REFERENCES) $(PROJECT_REFERENCES) $(build_xamlg_list) $(build_satellite_assembly_list)
	mkdir -p $(shell dirname $(ASSEMBLY))
	$(ASSEMBLY_COMPILER_COMMAND) $(ASSEMBLY_COMPILER_FLAGS) -out:$(ASSEMBLY) -target:$(COMPILE_TARGET) $(build_sources_embed) $(build_resources_embed) $(build_references_ref)
