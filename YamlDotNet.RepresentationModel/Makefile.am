
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- "-nowarn:1591" -debug "-define:DEBUG;TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Debug/YamlDotNet.RepresentationModel.dll
ASSEMBLY_MDB = $(ASSEMBLY).mdb
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll
BUILD_DIR = bin/Debug/

YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB_SOURCE=bin/Debug/YamlDotNet.RepresentationModel.dll.mdb
YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB=$(BUILD_DIR)/YamlDotNet.RepresentationModel.dll.mdb
YAMLDOTNET_CORE_DLL_SOURCE=../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll
YAMLDOTNET_CORE_DLL_MDB_SOURCE=../YamlDotNet.Core/bin/Debug/YamlDotNet.Core.dll.mdb
YAMLDOTNET_CORE_DLL_MDB=$(BUILD_DIR)/YamlDotNet.Core.dll.mdb

endif

if ENABLE_RELEASE
ASSEMBLY_COMPILER_COMMAND = gmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-nowarn:1591" "-define:TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Release/YamlDotNet.RepresentationModel.dll
ASSEMBLY_MDB = 
COMPILE_TARGET = library
PROJECT_REFERENCES =  \
	../YamlDotNet.Core/bin/Release/YamlDotNet.Core.dll
BUILD_DIR = bin/Release/

YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB=
YAMLDOTNET_CORE_DLL_SOURCE=../YamlDotNet.Core/bin/Release/YamlDotNet.Core.dll
YAMLDOTNET_CORE_DLL_MDB=

endif

AL=al2
SATELLITE_ASSEMBLY_NAME=$(notdir $(basename $(ASSEMBLY))).resources.dll

PROGRAMFILES = \
	$(YAMLDOTNET_REPRESENTATIONMODEL_DLL_MDB) \
	$(YAMLDOTNET_CORE_DLL) \
	$(YAMLDOTNET_CORE_DLL_MDB)  

LINUX_PKGCONFIG = \
	$(YAMLDOTNET_REPRESENTATIONMODEL_PC)  


RESGEN=resgen2
	
all: $(ASSEMBLY) $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

FILES = \
	../CommonAssemblyInfo.cs \
	AnchorNotFoundException.cs \
	DocumentLoadingState.cs \
	DuplicateAnchorException.cs \
	EmitterState.cs \
	IYamlVisitor.cs \
	Properties/AssemblyInfo.cs \
	Serialization/AnchorAssigner.cs \
	Serialization/AnchorAssigningObjectGraphVisitor.cs \
	Serialization/ChainedEventEmitter.cs \
	Serialization/ChainedObjectGraphVisitor.cs \
	Serialization/CustomSerializationObjectGraphVisitor.cs \
	Serialization/DefaultExclusiveObjectGraphVisitor.cs \
	Serialization/DefaultObjectFactory.cs \
	Serialization/Deserializer.cs \
	Serialization/EmittingObjectGraphVisitor.cs \
	Serialization/INamingConvention.cs \
	Serialization/IObjectFactory.cs \
	Serialization/ITypeDescriptor.cs \
	Serialization/LambdaObjectFactory.cs \
	Serialization/NamingConventions/CamelCaseNamingConvention.cs \
	Serialization/NamingConventions/HyphenatedNamingConvention.cs \
	Serialization/NamingConventions/NullNamingConvention.cs \
	Serialization/NamingConventions/PascalCaseNamingConvention.cs \
	Serialization/NamingConventions/UnderscoredNamingConvention.cs \
	Serialization/NamingConventionTypeDescriptor.cs \
	Serialization/PropertyDescriptor.cs \
	Serialization/ReadableAndWritablePropertiesTypeDescriptor.cs \
	Serialization/ReadablePropertiesTypeDescriptor.cs \
	Serialization/Serializer.cs \
	Serialization/TypeConverter.cs \
	Serialization/WriterEventEmitter.cs \
	Serialization/EventInfo.cs \
	Serialization/FullObjectGraphTraversalStrategy.cs \
	Serialization/IAliasProvider.cs \
	Serialization/IEventEmitter.cs \
	Serialization/IObjectGraphTraversalStrategy.cs \
	Serialization/IObjectGraphVisitor.cs \
	Serialization/IYamlTypeConverter.cs \
	Serialization/IYamlSerializable.cs \
	Serialization/ReflectionUtility.cs \
	Serialization/RoundtripObjectGraphTraversalStrategy.cs \
	Serialization/StreamFragment.cs \
	Serialization/ObjectAnchorCollection.cs \
	Serialization/TagMappings.cs \
	Serialization/TypeAssigningEventEmitter.cs \
	Serialization/YamlAliasAttribute.cs \
	Serialization/YamlAttributesTypeDescriptor.cs \
	Serialization/YamlIgnoreAttribute.cs \
	Serialization/StringExtensions.cs \
	YamlAliasNode.cs \
	YamlDocument.cs \
	YamlMappingNode.cs \
	YamlNode.cs \
	YamlNodeIdentityEqualityComparer.cs \
	YamlScalarNode.cs \
	YamlSequenceNode.cs \
	YamlStream.cs \
	YamlVisitor.cs \
	Serialization/NodeDeserializers/TypeConverterNodeDeserializer.cs \
	Serialization/NodeDeserializers/ArrayNodeDeserializer.cs \
	Serialization/NodeDeserializers/EnumerableNodeDeserializer.cs \
	Serialization/NodeDeserializers/NonGenericListNodeDeserializer.cs \
	Serialization/NodeDeserializers/GenericCollectionNodeDeserializer.cs \
	Serialization/NodeDeserializers/NonGenericDictionaryNodeDeserializer.cs \
	Serialization/NodeDeserializers/GenericDictionaryNodeDeserializer.cs \
	Serialization/NodeDeserializers/ObjectNodeDeserializer.cs \
	Serialization/NodeDeserializers/ScalarNodeDeserializer.cs \
	Serialization/NodeDeserializers/NullNodeDeserializer.cs \
	Serialization/INodeDeserializer.cs \
	Serialization/INodeTypeResolver.cs \
	Serialization/NodeTypeResolvers/TagNodeTypeResolver.cs \
	Serialization/NodeTypeResolvers/DefaultContainersNodeTypeResolver.cs \
	Serialization/NodeTypeResolvers/TypeNameInTagNodeTypeResolver.cs \
	Serialization/TypeDescriptorSkeleton.cs \
	Serialization/NodeValueDeserializer.cs \
	Serialization/AliasValueDeserializer.cs \
	Serialization/IValueDeserializer.cs \
	Serialization/SerializerState.cs 

DATA_FILES = 

RESOURCES = 

EXTRAS = \
	../YamlDotNet.snk \
	yamldotnet.representationmodel.pc.in 

REFERENCES =  \
	System \
	System.Core \
	System.Data \
	System.Xml

DLL_REFERENCES = 

CLEANFILES = $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

include $(top_srcdir)/Makefile.include

YAMLDOTNET_CORE_DLL = $(BUILD_DIR)/YamlDotNet.Core.dll
YAMLDOTNET_REPRESENTATIONMODEL_PC = $(BUILD_DIR)/yamldotnet.representationmodel.pc

$(eval $(call emit-deploy-target,YAMLDOTNET_CORE_DLL))
$(eval $(call emit-deploy-target,YAMLDOTNET_CORE_DLL_MDB))
$(eval $(call emit-deploy-wrapper,YAMLDOTNET_REPRESENTATIONMODEL_PC,yamldotnet.representationmodel.pc))


$(eval $(call emit_resgen_targets))
$(build_xamlg_list): %.xaml.g.cs: %.xaml
	xamlg '$<'

$(ASSEMBLY_MDB): $(ASSEMBLY)

$(ASSEMBLY): $(build_sources) $(build_resources) $(build_datafiles) $(DLL_REFERENCES) $(PROJECT_REFERENCES) $(build_xamlg_list) $(build_satellite_assembly_list)
	mkdir -p $(shell dirname $(ASSEMBLY))
	$(ASSEMBLY_COMPILER_COMMAND) $(ASSEMBLY_COMPILER_FLAGS) -out:$(ASSEMBLY) -target:$(COMPILE_TARGET) $(build_sources_embed) $(build_resources_embed) $(build_references_ref)
