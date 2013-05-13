
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- -debug "-define:DEBUG;TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Debug/YamlDotNet.Core.dll
ASSEMBLY_MDB = $(ASSEMBLY).mdb
COMPILE_TARGET = library
PROJECT_REFERENCES = 
BUILD_DIR = bin/Debug/

YAMLDOTNET_CORE_DLL_MDB_SOURCE=bin/Debug/YamlDotNet.Core.dll.mdb
YAMLDOTNET_CORE_DLL_MDB=$(BUILD_DIR)/YamlDotNet.Core.dll.mdb

endif

if ENABLE_RELEASE
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-define:TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Release/YamlDotNet.Core.dll
ASSEMBLY_MDB = 
COMPILE_TARGET = library
PROJECT_REFERENCES = 
BUILD_DIR = bin/Release/

YAMLDOTNET_CORE_DLL_MDB=

endif

AL=al2
SATELLITE_ASSEMBLY_NAME=$(notdir $(basename $(ASSEMBLY))).resources.dll

PROGRAMFILES = \
	$(YAMLDOTNET_CORE_DLL_MDB)  

LINUX_PKGCONFIG = \
	$(YAMLDOTNET_CORE_PC)  


RESGEN=resgen2
	
all: $(ASSEMBLY) $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

FILES = \
	../CommonAssemblyInfo.cs \
	CharacterAnalyzer.cs \
	Constants.cs \
	Emitter.cs \
	EmitterState.cs \
	EventReader.cs \
	Events/AnchorAlias.cs \
	Events/DocumentEnd.cs \
	Events/DocumentStart.cs \
	Events/EventType.cs \
	Events/IAnchorAlias.cs \
	Events/IDocumentEnd.cs \
	Events/IDocumentStart.cs \
	Events/IMappingEnd.cs \
	Events/IMappingStart.cs \
	Events/INodeEvent.cs \
	Events/IParsingEvent.cs \
	Events/IScalar.cs \
	Events/ISequenceEnd.cs \
	Events/ISequenceStart.cs \
	Events/IStreamEnd.cs \
	Events/IStreamStart.cs \
	Events/MappingStyle.cs \
	Events/NodeEvent.cs \
	Events/ParsingEvent.cs \
	Events/MappingEnd.cs \
	Events/MappingStart.cs \
	Events/Scalar.cs \
	Events/SequenceEnd.cs \
	Events/SequenceStart.cs \
	Events/SequenceStyle.cs \
	Events/StreamEnd.cs \
	Events/StreamStart.cs \
	FakeList.cs \
	ILookAheadBuffer.cs \
	InsertionQueue.cs \
	LookAheadBuffer.cs \
	Mark.cs \
	Parser.cs \
	ParserState.cs \
	Properties/AssemblyInfo.cs \
	Scanner.cs \
	SemanticErrorException.cs \
	SimpleKey.cs \
	StringLookAheadBuffer.cs \
	SyntaxErrorException.cs \
	TagDirectiveCollection.cs \
	Tokens/AnchorAlias.cs \
	Tokens/Anchor.cs \
	Tokens/BlockEnd.cs \
	Tokens/BlockEntry.cs \
	Tokens/BlockMappingStart.cs \
	Tokens/BlockSequenceStart.cs \
	Tokens/DocumentEnd.cs \
	Tokens/DocumentStart.cs \
	Tokens/FlowEntry.cs \
	Tokens/FlowMappingEnd.cs \
	Tokens/FlowMappingStart.cs \
	Tokens/FlowSequenceEnd.cs \
	Tokens/FlowSequenceStart.cs \
	Tokens/Key.cs \
	Tokens/Scalar.cs \
	ScalarStyle.cs \
	Tokens/StreamEnd.cs \
	Tokens/StreamStart.cs \
	Tokens/Tag.cs \
	Tokens/TagDirective.cs \
	Tokens/Token.cs \
	Tokens/Value.cs \
	Tokens/VersionDirective.cs \
	Version.cs \
	YamlException.cs 

DATA_FILES = 

RESOURCES = 

EXTRAS = \
	../YamlDotNet.snk \
	yamldotnet.core.pc.in 

REFERENCES =  \
	System \
	System.Core \
	System.Data \
	System.Xml

DLL_REFERENCES = 

CLEANFILES = $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

include $(top_srcdir)/Makefile.include

YAMLDOTNET_CORE_PC = $(BUILD_DIR)/yamldotnet.core.pc

$(eval $(call emit-deploy-wrapper,YAMLDOTNET_CORE_PC,yamldotnet.core.pc))


$(eval $(call emit_resgen_targets))
$(build_xamlg_list): %.xaml.g.cs: %.xaml
	xamlg '$<'

$(ASSEMBLY_MDB): $(ASSEMBLY)

$(ASSEMBLY): $(build_sources) $(build_resources) $(build_datafiles) $(DLL_REFERENCES) $(PROJECT_REFERENCES) $(build_xamlg_list) $(build_satellite_assembly_list)
	mkdir -p $(shell dirname $(ASSEMBLY))
	$(ASSEMBLY_COMPILER_COMMAND) $(ASSEMBLY_COMPILER_FLAGS) -out:$(ASSEMBLY) -target:$(COMPILE_TARGET) $(build_sources_embed) $(build_resources_embed) $(build_references_ref)
