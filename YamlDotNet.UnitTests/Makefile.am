
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- -debug "-define:DEBUG;TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Debug/YamlDotNet.UnitTests.dll
ASSEMBLY_MDB = $(ASSEMBLY).mdb
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet.Converters/bin/Debug/YamlDotNet.Converters.dll \
	../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll \
	../YamlDotNet.RepresentationModel/bin/Debug/YamlDotNet.RepresentationModel.dll
BUILD_DIR = bin/Debug/

YAMLDOTNET_UNITTESTS_DLL_MDB_SOURCE=bin/Debug/YamlDotNet.UnitTests.dll.mdb
YAMLDOTNET_UNITTESTS_DLL_MDB=$(BUILD_DIR)/YamlDotNet.UnitTests.dll.mdb
XUNIT_DLL_SOURCE=../Dependencies/xUnit/xunit.dll
XUNIT_EXTENSIONS_DLL_SOURCE=../Dependencies/xUnit/xunit.extensions.dll
YAMLDOTNET_CONVERTERS_DLL_SOURCE=../YamlDotNet.Converters/bin/Debug/YamlDotNet.Converters.dll
YAMLDOTNET_CONVERTERS_DLL_MDB_SOURCE=../YamlDotNet.Converters/bin/Debug/YamlDotNet.Converters.dll.mdb
YAMLDOTNET_CONVERTERS_DLL_MDB=$(BUILD_DIR)/YamlDotNet.Converters.dll.mdb
YAMLDOTNET_REPRESENTATIONMODEL_DLL_SOURCE=../YamlDotNet.RepresentationModel/bin/Debug/YamlDotNet.RepresentationModel.dll
YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB_SOURCE=../YamlDotNet.RepresentationModel/bin/Debug/YamlDotNet.RepresentationModel.dll.mdb
YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB=$(BUILD_DIR)/YamlDotNet.RepresentationModel.dll.mdb
YAMLDOTNET_CORE_DLL_SOURCE=../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll
YAMLDOTNET_CORE_DLL_MDB_SOURCE=../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll.mdb
YAMLDOTNET_CORE_DLL_MDB=$(BUILD_DIR)/YamlDotNet.Core.dll.mdb

endif

if ENABLE_RELEASE
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-define:TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Release/YamlDotNet.UnitTests.dll
ASSEMBLY_MDB = 
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet.Converters/bin/Release/YamlDotNet.Converters.dll \
	../YamlDotNet.Core/bin/Release/YamlDotNet.Core.dll \
	../YamlDotNet.RepresentationModel/bin/Release/YamlDotNet.RepresentationModel.dll
BUILD_DIR = bin/Release/

YAMLDOTNET_UNITTESTS_DLL_MDB=
XUNIT_DLL_SOURCE=../Dependencies/xUnit/xunit.dll
XUNIT_EXTENSIONS_DLL_SOURCE=../Dependencies/xUnit/xunit.extensions.dll
YAMLDOTNET_CONVERTERS_DLL_SOURCE=../YamlDotNet.Converters/bin/Release/YamlDotNet.Converters.dll
YAMLDOTNET_CONVERTERS_DLL_MDB=
YAMLDOTNET_REPRESENTATIONMODEL_DLL_SOURCE=../YamlDotNet.RepresentationModel/bin/Release/YamlDotNet.RepresentationModel.dll
YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB=
YAMLDOTNET_CORE_DLL_SOURCE=../YamlDotNet.Core/bin/Release/YamlDotNet.Core.dll
YAMLDOTNET_CORE_DLL_MDB=

endif

AL=al2
SATELLITE_ASSEMBLY_NAME=$(notdir $(basename $(ASSEMBLY))).resources.dll

PROGRAMFILES = \
	$(YAMLDOTNET_UNITTESTS_DLL_MDB) \
	$(XUNIT_DLL) \
	$(XUNIT_EXTENSIONS_DLL) \
	$(YAMLDOTNET_CONVERTERS_DLL) \
	$(YAMLDOTNET_CONVERTERS_DLL_MDB) \
	$(YAMLDOTNET_REPRESENTATIONMODEL_DLL) \
	$(YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB) \
	$(YAMLDOTNET_CORE_DLL) \
	$(YAMLDOTNET_CORE_DLL_MDB)  

LINUX_PKGCONFIG = \
	$(YAMLDOTNET_UNITTESTS_PC)  


RESGEN=resgen2
	
all: $(ASSEMBLY) $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

FILES = \
	Converters/Xml/XmlConverterTests.cs \
	Core/EmitterTests.cs \
	Core/InsertionQueueTests.cs \
	Core/LookAheadBufferTests.cs \
	Core/ParserTests.cs \
	Core/ScannerTests.cs \
	Properties/AssemblyInfo.cs \
	RepresentationModel/ObjectFactoryTests.cs \
	RepresentationModel/Samples.cs \
	RepresentationModel/SerializationTests.cs \
	RepresentationModel/NamingConventionTests.cs \
	RepresentationModel/YamlStreamTests.cs \
	Runner.cs \
	TracingVisitor.cs \
	YamlTest.cs 

DATA_FILES = 

RESOURCES = \
	files/empty.yaml,YamlDotNet.UnitTests.files.empty.yaml \
	files/test1.yaml,YamlDotNet.UnitTests.files.test1.yaml \
	files/test10.yaml,YamlDotNet.UnitTests.files.test10.yaml \
	files/test11.yaml,YamlDotNet.UnitTests.files.test11.yaml \
	files/test12.yaml,YamlDotNet.UnitTests.files.test12.yaml \
	files/test13.yaml,YamlDotNet.UnitTests.files.test13.yaml \
	files/test14.yaml,YamlDotNet.UnitTests.files.test14.yaml \
	files/test2.yaml,YamlDotNet.UnitTests.files.test2.yaml \
	files/test3.yaml,YamlDotNet.UnitTests.files.test3.yaml \
	files/test4.yaml,YamlDotNet.UnitTests.files.test4.yaml \
	files/test5.yaml,YamlDotNet.UnitTests.files.test5.yaml \
	files/test6.yaml,YamlDotNet.UnitTests.files.test6.yaml \
	files/test7.yaml,YamlDotNet.UnitTests.files.test7.yaml \
	files/test8.yaml,YamlDotNet.UnitTests.files.test8.yaml \
	files/test9.yaml,YamlDotNet.UnitTests.files.test9.yaml \
	files/backwardsAlias.yaml,YamlDotNet.UnitTests.files.backwardsAlias.yaml \
	files/forwardAlias.yaml,YamlDotNet.UnitTests.files.forwardAlias.yaml \
	files/explicitType.yaml,YamlDotNet.UnitTests.files.explicitType.yaml \
	files/dictionary.yaml,YamlDotNet.UnitTests.files.dictionary.yaml \
	files/dictionaryExplicit.yaml,YamlDotNet.UnitTests.files.dictionaryExplicit.yaml \
	files/listOfDictionaries.yaml,YamlDotNet.UnitTests.files.listOfDictionaries.yaml \
	files/list.yaml,YamlDotNet.UnitTests.files.list.yaml \
	files/listExplicit.yaml,YamlDotNet.UnitTests.files.listExplicit.yaml \
	files/tags.yaml,YamlDotNet.UnitTests.files.tags.yaml \
	files/convertible.yaml,YamlDotNet.UnitTests.files.convertible.yaml \
	files/converter.yaml,YamlDotNet.UnitTests.files.converter.yaml \
	files/sample.yaml,YamlDotNet.UnitTests.files.sample.yaml \
	files/backreference.yaml,YamlDotNet.UnitTests.files.backreference.yaml \
	files/fail-backreference.yaml,YamlDotNet.UnitTests.files.fail-backreference.yaml \
	files/invalid-reference.yaml,YamlDotNet.UnitTests.files.invalid-reference.yaml \
	files/local-tags.yaml,YamlDotNet.UnitTests.files.local-tags.yaml \
	files/namingConvention.yaml,YamlDotNet.UnitTests.files.namingConvention.yaml 

EXTRAS = \
	../YamlDotNet.snk \
	yamldotnet.unittests.pc.in 

REFERENCES =  \
	System \
	System.Core \
	System.Data \
	System.Drawing \
	System.Xml

DLL_REFERENCES =  \
	../Dependencies/xUnit/xunit.dll \
	../Dependencies/xUnit/xunit.extensions.dll

CLEANFILES = $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

include $(top_srcdir)/Makefile.include

XUNIT_DLL = $(BUILD_DIR)/xunit.dll
XUNIT_EXTENSIONS_DLL = $(BUILD_DIR)/xunit.extensions.dll
YAMLDOTNET_CONVERTERS_DLL = $(BUILD_DIR)/YamlDotNet.Converters.dll
YAMLDOTNET_REPRESENTATIONMODEL_DLL = $(BUILD_DIR)/YamlDotNet.RepresentationModel.dll
YAMLDOTNET_CORE_DLL = $(BUILD_DIR)/YamlDotNet.Core.dll
YAMLDOTNET_UNITTESTS_PC = $(BUILD_DIR)/yamldotnet.unittests.pc

$(eval $(call emit-deploy-target,XUNIT_DLL))
$(eval $(call emit-deploy-target,XUNIT_EXTENSIONS_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_CONVERTERS_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_CONVERTERS_DLL_MDB))
$(eval $(call emit-deploy-target,YAMLDOTNET_REPRESENTATIONMODEL_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB))
$(eval $(call emit-deploy-target,YAMLDOTNET_CORE_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_CORE_DLL_MDB))
$(eval $(call emit-deploy-wrapper,YAMLDOTNET_UNITTESTS_PC,yamldotnet.unittests.pc))


$(eval $(call emit_resgen_targets))
$(build_xamlg_list): %.xaml.g.cs: %.xaml
	xamlg '$<'

$(ASSEMBLY_MDB): $(ASSEMBLY)

$(ASSEMBLY): $(build_sources) $(build_resources) $(build_datafiles) $(DLL_REFERENCES) $(PROJECT_REFERENCES) $(build_xamlg_list) $(build_satellite_assembly_list)
	mkdir -p $(shell dirname $(ASSEMBLY))
	$(ASSEMBLY_COMPILER_COMMAND) $(ASSEMBLY_COMPILER_FLAGS) -out:$(ASSEMBLY) -target:$(COMPILE_TARGET) $(build_sources_embed) $(build_resources_embed) $(build_references_ref)
