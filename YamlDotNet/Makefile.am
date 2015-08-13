
EXTRA_DIST =  

# Warning: This is an automatically generated file, do not edit!

if ENABLE_DEBUG
ASSEMBLY_COMPILER_COMMAND = dmcs
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize- "-nowarn:1591;219;649" -debug "-define:DEBUG;TRACE"
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
ASSEMBLY_COMPILER_FLAGS =  -noconfig -codepage:utf8 -warn:4 -optimize+ "-nowarn:1591;219;649" "-define:TRACE"
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
	Core/AnchorNotFoundException.cs \
	Core/CharacterAnalyzer.cs \
	Core/Constants.cs \
	Core/Cursor.cs \
	Core/DuplicateAnchorException.cs \
	Core/Emitter.cs \
	Core/EmitterState.cs \
	Core/EventReader.cs \
	Core/Events/AnchorAlias.cs \
	Core/Events/Comment.cs \
	Core/Events/DocumentEnd.cs \
	Core/Events/DocumentStart.cs \
	Core/Events/EventType.cs \
	Core/Events/IParsingEventVisitor.cs \
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
	Core/ForwardAnchorNotSupportedException.cs \
	Core/HashCode.cs \
	Core/IEmitter.cs \
	Core/ILookAheadBuffer.cs \
	Core/InsertionQueue.cs \
	Core/IParser.cs \
	Core/IScanner.cs \
	Core/LookAheadBuffer.cs \
	Core/Mark.cs \
	Core/MergingParser.cs \
	Core/Parser.cs \
	Core/ParserState.cs \
	Core/Tokens/Comment.cs \
	Helpers/Portability.cs \
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
	RepresentationModel/DocumentLoadingState.cs \
	RepresentationModel/EmitterState.cs \
	RepresentationModel/IYamlVisitor.cs \
	RepresentationModel/YamlAliasNode.cs \
	RepresentationModel/YamlDocument.cs \
	RepresentationModel/YamlMappingNode.cs \
	RepresentationModel/YamlNode.cs \
	RepresentationModel/YamlNodeIdentityEqualityComparer.cs \
	RepresentationModel/YamlScalarNode.cs \
	RepresentationModel/YamlSequenceNode.cs \
	RepresentationModel/YamlStream.cs \
	RepresentationModel/YamlVisitor.cs \
	Serialization/Converters/GuidConverter.cs \
	Serialization/Deserializer.cs \
	Serialization/EventEmitters/ChainedEventEmitter.cs \
	Serialization/EventEmitters/JsonEventEmitter.cs \
	Serialization/EventEmitters/TypeAssigningEventEmitter.cs \
	Serialization/EventEmitters/WriterEventEmitter.cs \
	Serialization/EventInfo.cs \
	Serialization/IAliasProvider.cs \
	Serialization/IEventEmitter.cs \
	Serialization/INamingConvention.cs \
	Serialization/INodeDeserializer.cs \
	Serialization/INodeTypeResolver.cs \
	Serialization/IObjectDescriptor.cs \
	Serialization/IObjectFactory.cs \
	Serialization/IObjectGraphTraversalStrategy.cs \
	Serialization/IObjectGraphVisitor.cs \
	Serialization/IPropertyDescriptor.cs \
	Serialization/ITypeInspector.cs \
	Serialization/ITypeResolver.cs \
	Serialization/IValueDeserializer.cs \
	Serialization/IValuePromise.cs \
	Serialization/IYamlSerializable.cs \
	Serialization/IYamlTypeConverter.cs \
	Serialization/NamingConventions/CamelCaseNamingConvention.cs \
	Serialization/NamingConventions/HyphenatedNamingConvention.cs \
	Serialization/NamingConventions/NullNamingConvention.cs \
	Serialization/NamingConventions/PascalCaseNamingConvention.cs \
	Serialization/NamingConventions/UnderscoredNamingConvention.cs \
	Serialization/NodeDeserializers/ArrayNodeDeserializer.cs \
	Serialization/NodeDeserializers/EnumerableNodeDeserializer.cs \
	Serialization/NodeDeserializers/GenericCollectionNodeDeserializer.cs \
	Serialization/NodeDeserializers/GenericDictionaryNodeDeserializer.cs \
	Serialization/NodeDeserializers/NonGenericDictionaryNodeDeserializer.cs \
	Serialization/NodeDeserializers/NonGenericListNodeDeserializer.cs \
	Serialization/NodeDeserializers/NullNodeDeserializer.cs \
	Serialization/NodeDeserializers/ObjectNodeDeserializer.cs \
	Serialization/NodeDeserializers/ScalarNodeDeserializer.cs \
	Serialization/NodeDeserializers/TypeConverterNodeDeserializer.cs \
	Serialization/NodeTypeResolvers/DefaultContainersNodeTypeResolver.cs \
	Serialization/NodeTypeResolvers/TagNodeTypeResolver.cs \
	Serialization/NodeTypeResolvers/TypeNameInTagNodeTypeResolver.cs \
	Serialization/ObjectDescriptor.cs \
	Serialization/ObjectFactories/DefaultObjectFactory.cs \
	Serialization/ObjectFactories/LambdaObjectFactory.cs \
	Serialization/ObjectGraphTraversalStrategies/FullObjectGraphTraversalStrategy.cs \
	Serialization/ObjectGraphTraversalStrategies/RoundtripObjectGraphTraversalStrategy.cs \
	Serialization/ObjectGraphVisitors/AnchorAssigner.cs \
	Serialization/ObjectGraphVisitors/AnchorAssigningObjectGraphVisitor.cs \
	Serialization/ObjectGraphVisitors/ChainedObjectGraphVisitor.cs \
	Serialization/ObjectGraphVisitors/CustomSerializationObjectGraphVisitor.cs \
	Serialization/ObjectGraphVisitors/DefaultExclusiveObjectGraphVisitor.cs \
	Serialization/ObjectGraphVisitors/EmittingObjectGraphVisitor.cs \
	Serialization/PropertyDescriptor.cs \
	Serialization/SerializationOptions.cs \
	Serialization/Serializer.cs \
	Serialization/StreamFragment.cs \
	Serialization/TagMappings.cs \
	Serialization/TypeInspectors/NamingConventionTypeInspector.cs \
	Serialization/TypeInspectors/ReadableAndWritablePropertiesTypeInspector.cs \
	Serialization/TypeInspectors/ReadablePropertiesTypeInspector.cs \
	Serialization/TypeInspectors/TypeInspectorSkeleton.cs \
	Serialization/TypeResolvers/DynamicTypeResolver.cs \
	Serialization/TypeResolvers/StaticTypeResolver.cs \
	Serialization/Utilities/IPostDeserializationCallback.cs \
	Serialization/Utilities/ObjectAnchorCollection.cs \
	Serialization/Utilities/ReflectionUtility.cs \
	Serialization/Utilities/SerializerState.cs \
	Serialization/Utilities/StringExtensions.cs \
	Serialization/Utilities/TypeConverter.cs \
	Serialization/Utilities/YamlTypeConverters.cs \
	Serialization/ValueDeserializers/AliasValueDeserializer.cs \
	Serialization/ValueDeserializers/NodeValueDeserializer.cs \
	Serialization/YamlAliasAttribute.cs \
	Serialization/YamlAttributesTypeInspector.cs \
	Serialization/YamlFormatter.cs \
	Serialization/YamlIgnoreAttribute.cs \
	Serialization/YamlMember.cs 

DATA_FILES = 

RESOURCES = 

EXTRAS = \
	yamldotnet.pc.in 

REFERENCES =  \
	System \
	System.Core \
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
