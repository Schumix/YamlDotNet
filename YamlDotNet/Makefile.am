
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = dmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- "-nowarn:1591;219;649" -debug "-define:DEBUG;TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Debug/YamlDotNet.dll
ASSEMBLY_MDB = $(ASSEMBLY).mdb
COMPILE_TARGET = library
PROJECT_REFERENCES = 
BUILD_DIR = bin/Debug/

YAMLDOTNET_DLL_MDB_SOURCE=bin/Debug/YamlDotNet.dll.mdb
YAMLDOTNET_DLL_MDB=$(BUILD_DIR)/YamlDotNet.dll.mdb

endif

if ENABLE_RELEASE
ASSEMBLY_COMPILER_COMMAND = dmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-nowarn:1591;219;649" "-define:TRACE" "-keyfile:../YamlDotNet.snk"
ASSEMBLY = bin/Release/YamlDotNet.dll
ASSEMBLY_MDB = 
COMPILE_TARGET = library
PROJECT_REFERENCES = 
BUILD_DIR = bin/Release/

YAMLDOTNET_DLL_MDB=

endif

AL=al
SATELLITE_ASSEMBLY_NAME=$(notdir $(basename $(ASSEMBLY))).resources.dll

PROGRAMFILES = \
	$(YAMLDOTNET_DLL_MDB)  

LINUX_PKGCONFIG = \
	$(YAMLDOTNET_PC)  


RESGEN=resgen2
	
all: $(ASSEMBLY) $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

FILES = \
	../CommonAssemblyInfo.cs \
	Core/CharacterAnalyzer.cs \
	Core/Constants.cs \
	Core/Emitter.cs \
	Core/EmitterState.cs \
	Core/EventReader.cs \
	Core/Events/AnchorAlias.cs \
	Core/Events/DocumentEnd.cs \
	Core/Events/DocumentStart.cs \
	Core/Events/EventType.cs \
	Core/Events/IAnchorAlias.cs \
	Core/Events/IDocumentEnd.cs \
	Core/Events/IDocumentStart.cs \
	Core/Events/IMappingEnd.cs \
	Core/Events/IMappingStart.cs \
	Core/Events/INodeEvent.cs \
	Core/Events/IParsingEvent.cs \
	Core/Events/IScalar.cs \
	Core/Events/ISequenceEnd.cs \
	Core/Events/ISequenceStart.cs \
	Core/Events/IStreamEnd.cs \
	Core/Events/IStreamStart.cs \
	Core/Events/MappingStyle.cs \
	Core/Events/NodeEvent.cs \
	Core/Events/ParsingEvent.cs \
	Core/Events/MappingEnd.cs \
	Core/Events/MappingStart.cs \
	Core/Events/Scalar.cs \
	Core/Events/SequenceEnd.cs \
	Core/Events/SequenceStart.cs \
	Core/Events/SequenceStyle.cs \
	Core/Events/StreamEnd.cs \
	Core/Events/StreamStart.cs \
	Core/FakeList.cs \
	Core/IEmitter.cs \
	Core/ILookAheadBuffer.cs \
	Core/InsertionQueue.cs \
	Core/IParser.cs \
	Core/IScanner.cs \
	Core/LookAheadBuffer.cs \
	Core/Mark.cs \
	Core/Parser.cs \
	Core/ParserState.cs \
	Properties/AssemblyInfo.cs \
	Core/Scanner.cs \
	Core/SemanticErrorException.cs \
	Core/SimpleKey.cs \
	Core/StringLookAheadBuffer.cs \
	Core/SyntaxErrorException.cs \
	Core/TagDirectiveCollection.cs \
	Core/Tokens/AnchorAlias.cs \
	Core/Tokens/Anchor.cs \
	Core/Tokens/BlockEnd.cs \
	Core/Tokens/BlockEntry.cs \
	Core/Tokens/BlockMappingStart.cs \
	Core/Tokens/BlockSequenceStart.cs \
	Core/Tokens/DocumentEnd.cs \
	Core/Tokens/DocumentStart.cs \
	Core/Tokens/FlowEntry.cs \
	Core/Tokens/FlowMappingEnd.cs \
	Core/Tokens/FlowMappingStart.cs \
	Core/Tokens/FlowSequenceEnd.cs \
	Core/Tokens/FlowSequenceStart.cs \
	Core/Tokens/Key.cs \
	Core/Tokens/Scalar.cs \
	Core/ScalarStyle.cs \
	Core/Tokens/StreamEnd.cs \
	Core/Tokens/StreamStart.cs \
	Core/Tokens/Tag.cs \
	Core/Tokens/TagDirective.cs \
	Core/Tokens/Token.cs \
	Core/Tokens/Value.cs \
	Core/Tokens/VersionDirective.cs \
	Core/Version.cs \
	Core/YamlException.cs \
	RepresentationModel/AnchorNotFoundException.cs \
	RepresentationModel/DocumentLoadingState.cs \
	RepresentationModel/DuplicateAnchorException.cs \
	RepresentationModel/EmitterState.cs \
	RepresentationModel/ForwardAnchorNotSupportedException.cs \
	RepresentationModel/IYamlVisitor.cs \
	RepresentationModel/Serialization/Deserializer.cs \
	RepresentationModel/Serialization/EventEmitters/ChainedEventEmitter.cs \
	RepresentationModel/Serialization/EventEmitters/JsonEventEmitter.cs \
	RepresentationModel/Serialization/EventEmitters/TypeAssigningEventEmitter.cs \
	RepresentationModel/Serialization/EventEmitters/WriterEventEmitter.cs \
	RepresentationModel/Serialization/EventInfo.cs \
	RepresentationModel/Serialization/IAliasProvider.cs \
	RepresentationModel/Serialization/IEventEmitter.cs \
	RepresentationModel/Serialization/INamingConvention.cs \
	RepresentationModel/Serialization/INodeDeserializer.cs \
	RepresentationModel/Serialization/INodeTypeResolver.cs \
	RepresentationModel/Serialization/IObjectDescriptor.cs \
	RepresentationModel/Serialization/IObjectFactory.cs \
	RepresentationModel/Serialization/IObjectGraphTraversalStrategy.cs \
	RepresentationModel/Serialization/IObjectGraphVisitor.cs \
	RepresentationModel/Serialization/IPropertyDescriptor.cs \
	RepresentationModel/Serialization/ITypeInspector.cs \
	RepresentationModel/Serialization/ITypeResolver.cs \
	RepresentationModel/Serialization/IValueDeserializer.cs \
	RepresentationModel/Serialization/IValuePromise.cs \
	RepresentationModel/Serialization/IYamlSerializable.cs \
	RepresentationModel/Serialization/IYamlTypeConverter.cs \
	RepresentationModel/Serialization/NamingConventions/CamelCaseNamingConvention.cs \
	RepresentationModel/Serialization/NamingConventions/HyphenatedNamingConvention.cs \
	RepresentationModel/Serialization/NamingConventions/NullNamingConvention.cs \
	RepresentationModel/Serialization/NamingConventions/PascalCaseNamingConvention.cs \
	RepresentationModel/Serialization/NamingConventions/UnderscoredNamingConvention.cs \
	RepresentationModel/Serialization/NodeDeserializers/ArrayNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/EnumerableNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/GenericCollectionNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/GenericDictionaryNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/NonGenericDictionaryNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/NonGenericListNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/NullNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/ObjectNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/ScalarNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeDeserializers/TypeConverterNodeDeserializer.cs \
	RepresentationModel/Serialization/NodeTypeResolvers/DefaultContainersNodeTypeResolver.cs \
	RepresentationModel/Serialization/NodeTypeResolvers/TagNodeTypeResolver.cs \
	RepresentationModel/Serialization/NodeTypeResolvers/TypeNameInTagNodeTypeResolver.cs \
	RepresentationModel/Serialization/ObjectDescriptor.cs \
	RepresentationModel/Serialization/ObjectFactories/DefaultObjectFactory.cs \
	RepresentationModel/Serialization/ObjectFactories/LambdaObjectFactory.cs \
	RepresentationModel/Serialization/ObjectGraphTraversalStrategies/FullObjectGraphTraversalStrategy.cs \
	RepresentationModel/Serialization/ObjectGraphTraversalStrategies/RoundtripObjectGraphTraversalStrategy.cs \
	RepresentationModel/Serialization/ObjectGraphVisitors/AnchorAssigner.cs \
	RepresentationModel/Serialization/ObjectGraphVisitors/AnchorAssigningObjectGraphVisitor.cs \
	RepresentationModel/Serialization/ObjectGraphVisitors/ChainedObjectGraphVisitor.cs \
	RepresentationModel/Serialization/ObjectGraphVisitors/CustomSerializationObjectGraphVisitor.cs \
	RepresentationModel/Serialization/ObjectGraphVisitors/DefaultExclusiveObjectGraphVisitor.cs \
	RepresentationModel/Serialization/ObjectGraphVisitors/EmittingObjectGraphVisitor.cs \
	RepresentationModel/Serialization/PropertyDescriptor.cs \
	RepresentationModel/Serialization/SerializationOptions.cs \
	RepresentationModel/Serialization/Serializer.cs \
	RepresentationModel/Serialization/StreamFragment.cs \
	RepresentationModel/Serialization/TagMappings.cs \
	RepresentationModel/Serialization/TypeInspectors/NamingConventionTypeInspector.cs \
	RepresentationModel/Serialization/TypeInspectors/ReadableAndWritablePropertiesTypeInspector.cs \
	RepresentationModel/Serialization/TypeInspectors/ReadablePropertiesTypeInspector.cs \
	RepresentationModel/Serialization/TypeInspectors/TypeInspectorSkeleton.cs \
	RepresentationModel/Serialization/TypeResolvers/DynamicTypeResolver.cs \
	RepresentationModel/Serialization/TypeResolvers/StaticTypeResolver.cs \
	RepresentationModel/Serialization/Utilities/ObjectAnchorCollection.cs \
	RepresentationModel/Serialization/Utilities/ReflectionUtility.cs \
	RepresentationModel/Serialization/Utilities/SerializerState.cs \
	RepresentationModel/Serialization/Utilities/StringExtensions.cs \
	RepresentationModel/Serialization/Utilities/TypeConverter.cs \
	RepresentationModel/Serialization/ValueDeserializers/AliasValueDeserializer.cs \
	RepresentationModel/Serialization/ValueDeserializers/NodeValueDeserializer.cs \
	RepresentationModel/Serialization/YamlAliasAttribute.cs \
	RepresentationModel/Serialization/YamlAttributesTypeInspector.cs \
	RepresentationModel/Serialization/YamlFormatter.cs \
	RepresentationModel/Serialization/YamlIgnoreAttribute.cs \
	RepresentationModel/Serialization/YamlMember.cs \
	RepresentationModel/YamlAliasNode.cs \
	RepresentationModel/YamlDocument.cs \
	RepresentationModel/YamlMappingNode.cs \
	RepresentationModel/YamlNode.cs \
	RepresentationModel/YamlNodeIdentityEqualityComparer.cs \
	RepresentationModel/YamlScalarNode.cs \
	RepresentationModel/YamlSequenceNode.cs \
	RepresentationModel/YamlStream.cs \
	RepresentationModel/YamlVisitor.cs 

DATA_FILES = 

RESOURCES = 

EXTRAS = \
	../YamlDotNet.snk \
	yamldotnet.pc.in 

REFERENCES =  \
	System \
	System.Configuration \
	System.Core \
	System.Data \
	System.Xml

DLL_REFERENCES = 

CLEANFILES = $(PROGRAMFILES) $(LINUX_PKGCONFIG) 

include $(top_srcdir)/Makefile.include

YAMLDOTNET_PC = $(BUILD_DIR)/yamldotnet.pc

$(eval $(call emit-deploy-wrapper,YAMLDOTNET_PC,yamldotnet.pc))


$(eval $(call emit_resgen_targets))
$(build_xamlg_list): %.xaml.g.cs: %.xaml
	xamlg '$<'

$(ASSEMBLY_MDB): $(ASSEMBLY)

$(ASSEMBLY): $(build_sources) $(build_resources) $(build_datafiles) $(DLL_REFERENCES) $(PROJECT_REFERENCES) $(build_xamlg_list) $(build_satellite_assembly_list)
	mkdir -p $(shell dirname $(ASSEMBLY))
	$(ASSEMBLY_COMPILER_COMMAND) $(ASSEMBLY_COMPILER_FLAGS) -out:$(ASSEMBLY) -target:$(COMPILE_TARGET) $(build_sources_embed) $(build_resources_embed) $(build_references_ref)
