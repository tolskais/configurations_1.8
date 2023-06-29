Exception in thread "main" java.lang.NoSuchMethodError: java.nio.ByteBuffer.flip()Ljava/nio/ByteBuffer;
at org.apache.commons.configuration2.io.FileUtils.decodeUrl(FileUtils.java:88)
at org.apache.commons.configuration2.io.FileUtils.toFile(FileUtils.java:54)
at org.apache.commons.configuration2.io.FileLocatorUtils.fileFromURL(FileLocatorUtils.java:211)
at org.apache.commons.configuration2.io.DefaultFileSystem.getInputStream(DefaultFileSystem.java:47)
at org.apache.commons.configuration2.io.DefaultFileSystem.getInputStream(DefaultFileSystem.java:41)
at org.apache.commons.configuration2.io.FileHandler.load(FileHandler.java:692)
at org.apache.commons.configuration2.io.FileHandler.load(FileHandler.java:596)
at org.apache.commons.configuration2.io.FileHandler.load(FileHandler.java:569)
at org.apache.commons.configuration2.builder.FileBasedConfigurationBuilder.initFileHandler(FileBasedConfigurationBuilder.java:248)
at org.apache.commons.configuration2.builder.FileBasedConfigurationBuilder.initResultInstance(FileBasedConfigurationBuilder.java:232)
at org.apache.commons.configuration2.builder.FileBasedConfigurationBuilder.initResultInstance(FileBasedConfigurationBuilder.java:53)
at org.apache.commons.configuration2.builder.BasicConfigurationBuilder.createResult(BasicConfigurationBuilder.java:340)
at org.apache.commons.configuration2.builder.BasicConfigurationBuilder.getConfiguration(BasicConfigurationBuilder.java:233)
at Test.main(Test.java:15)

Process finished with exit code 1
