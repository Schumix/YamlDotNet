
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = dmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- -debug "-define:DEBUG;TRACE"
ASSEMBLY = bin/Debug/YamlDotNet.Dynamic.dll
ASSEMBLY_MDB = $(ASSEMBLY).mdb
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet/bin/Debug/YamlDotNet.dll
BUILD_DIR = bin/Debug/

YAMLDOTNET_DYNAMIC_DLL_MDB_SOURCE=bin/Debug/YamlDotNet.Dynamic.dll.mdb
YAMLDOTNET_DYNAMIC_DLL_MDB=$(BUILD_DIR)/YamlDotNet.Dynamic.dll.mdb
YAMLDOTNET_DLL_SOURCE=../YamlDotNet/bin/Debug/YamlDotNet.dll
YAMLDOTNET_DLL_MDB_SOURCE=../YamlDotNet/bin/Debug/YamlDotNet.dll.mdb
YAMLDOTNET_DLL_MDB=$(BUILD_DIR)/YamlDotNet.dll.mdb

endif

if ENABLE_RELEASE
ASSEMBLY_COMPILER_COMMAND = dmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-define:TRACE"
ASSEMBLY = bin/Release/YamlDotNet.Dynamic.dll
ASSEMBLY_MDB = 
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet/bin/Release/YamlDotNet.dll
BUILD_DIR = bin/Release/

YAMLDOTNET_DYNAMIC_DLL_MDB=
YAMLDOTNET_DLL_SOURCE=../YamlDotNet/bin/Release/YamlDotNet.dll
YAMLDOTNET_DLL_MDB=

endif

AL=al
SATELLITE_ASSEMBLY_NAME=$(notdir $(basename $(ASSEMBLY))).resources.dll

PROGRAMFILES = \
	$(YAMLDOTNET_DYNAMIC_DLL_MDB) \
	$(YAMLDOTNET_DLL) \
	$(YAMLDOTNET_DLL_MDB)  

LINUX_PKGCONFIG = \
	$(YAMLDOTNET_DYNAMIC_PC)  


RESGEN=resgen2
	
all: $(ASSEMBLY) $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

FILES = \
	DynamicYaml.cs \
	Extensions.cs \
	Properties/AssemblyInfo.cs \
	YamlDoc.cs 

DATA_FILES = 

RESOURCES = 

EXTRAS = \
	yamldotnet.dynamic.pc.in 

REFERENCES =  \
	System \
	System.Core \
	System.Xml.Linq \
	System.Data.DataSetExtensions \
	Microsoft.CSharp \
	System.Data \
	System.Xml

DLL_REFERENCES = 

CLEANFILES = $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

include $(top_srcdir)/Makefile.include

YAMLDOTNET_DLL = $(BUILD_DIR)/YamlDotNet.dll
YAMLDOTNET_DYNAMIC_PC = $(BUILD_DIR)/yamldotnet.dynamic.pc

$(eval $(call emit-deploy-target,YAMLDOTNET_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_DLL_MDB))
$(eval $(call emit-deploy-wrapper,YAMLDOTNET_DYNAMIC_PC,yamldotnet.dynamic.pc))


$(eval $(call emit_resgen_targets))
$(build_xamlg_list): %.xaml.g.cs: %.xaml
	xamlg '$<'

$(ASSEMBLY_MDB): $(ASSEMBLY)

$(ASSEMBLY): $(build_sources) $(build_resources) $(build_datafiles) $(DLL_REFERENCES) $(PROJECT_REFERENCES) $(build_xamlg_list) $(build_satellite_assembly_list)
	mkdir -p $(shell dirname $(ASSEMBLY))
	$(ASSEMBLY_COMPILER_COMMAND) $(ASSEMBLY_COMPILER_FLAGS) -out:$(ASSEMBLY) -target:$(COMPILE_TARGET) $(build_sources_embed) $(build_resources_embed) $(build_references_ref)
