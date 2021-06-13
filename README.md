# SLF4J: Class path contains multiple SLF4J bindings.
SLF4J: Found binding in [jar:file:/C:/Users/Michael%20Ruffalo/.p2/pool/plugins/org.eclipse.m2e.maven.runtime.slf4j.simple_1.16.0.20200610-1735/jars/slf4j-simple-1.7.5.jar!/org/slf4j/impl/StaticLoggerBinder.class]
SLF4J: Found binding in [file:/C:/Users/Michael%20Ruffalo/eclipse/java-2020-122/eclipse/configuration/org.eclipse.osgi/5/0/.cp/org/slf4j/impl/StaticLoggerBinder.class]
SLF4J: See http://www.slf4j.org/codes.html#multiple_bindings for an explanation.
SLF4J: Actual binding is of type [org.slf4j.impl.SimpleLoggerFactory]
SLF4J: Class path contains multiple SLF4J bindings.
SLF4J: Found binding in [jar:file:/C:/Users/Michael%20Ruffalo/.p2/pool/plugins/org.eclipse.m2e.maven.runtime.slf4j.simple_1.16.0.20200610-1735/jars/slf4j-simple-1.7.5.jar!/org/slf4j/impl/StaticLoggerBinder.class]
SLF4J: Found binding in [file:/C:/Users/Michael%20Ruffalo/eclipse/java-2020-122/eclipse/configuration/org.eclipse.osgi/5/0/.cp/org/slf4j/impl/StaticLoggerBinder.class]
SLF4J: See http://www.slf4j.org/codes.html#multiple_bindings for an explanation.
SLF4J: Actual binding is of type [org.slf4j.impl.SimpleLoggerFactory]
[INFO] Scanning for projects...
[INFO] 
[INFO] -----------------------< com.snhu:rest-service >------------------------
[INFO] Building rest-service 0.0.1-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-resources-plugin:3.1.0:resources (default-resources) @ rest-service ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Copying 1 resource
[INFO] Copying 0 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.1:compile (default-compile) @ rest-service ---
[INFO] Nothing to compile - all classes are up to date
[INFO] 
[INFO] --- maven-resources-plugin:3.1.0:testResources (default-testResources) @ rest-service ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\Users\Michael Ruffalo\Downloads\CS 305 Module Six Code (1)\rest-service\src\test\resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.1:testCompile (default-testCompile) @ rest-service ---
[INFO] Nothing to compile - all classes are up to date
[INFO] 
[INFO] --- maven-surefire-plugin:2.22.2:test (default-test) @ rest-service ---
[INFO] 
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] 
[INFO] Results:
[INFO] 
[INFO] Tests run: 0, Failures: 0, Errors: 0, Skipped: 0
[INFO] 
[INFO] 
[INFO] --- maven-jar-plugin:3.1.2:jar (default-jar) @ rest-service ---
[INFO] Building jar: C:\Users\Michael Ruffalo\Downloads\CS 305 Module Six Code (1)\rest-service\target\rest-service-0.0.1-SNAPSHOT.jar
[INFO] 
[INFO] --- spring-boot-maven-plugin:2.2.4.RELEASE:repackage (repackage) @ rest-service ---
[INFO] Replacing main artifact with repackaged archive
[INFO] 
[INFO] --- dependency-check-maven:5.3.0:check (default) @ rest-service ---
[INFO] Instance is null, returning unconfigured instance
[INFO] thread_pool.default PoolConfiguration = useBoundary = [false] boundarySize = [2000] maximumPoolSize = [150] minimumPoolSize = [4] keepAliveTime = [300000] whenBlockedPolicy = [RUN] startUpSize = [4]
[INFO] Setting default auxiliaries to ODC
[INFO] setting defaultCompositeCacheAttributes to [ useLateral = true, useRemote = true, useDisk = true, maxObjs = 0, maxSpoolPerRun = -1, diskUsagePattern = UPDATE, spoolChunkSize = 2 ]
[INFO] setting defaultElementAttributes to [ IS_LATERAL = false, IS_SPOOL = true, IS_REMOTE = false, IS_ETERNAL = false, MaxLifeSeconds = 86400, IdleTime = 1800, CreateTime = 1623590688746, LastAccessTime = 1623590688746, getTimeToLiveSeconds() = 86399, createTime = 1623590688746 ]
[INFO] initialized MemoryCache for CENTRAL
[INFO] Constructed cache with name [CENTRAL] and cache attributes [ useLateral = true, useRemote = true, useDisk = true, maxObjs = 0, maxSpoolPerRun = -1, diskUsagePattern = UPDATE, spoolChunkSize = 2 ]
[INFO] No cache event logger defined for auxiliary [jcs.auxiliary.ODC]
[INFO] Using standard serializer [org.apache.commons.jcs.utils.serialization.StandardSerializer@44abdb1f] for auxiliary [jcs.auxiliary.ODC]
[INFO] thread_pool.disk_cache_event_queue PoolConfiguration = useBoundary = [false] boundarySize = [2000] maximumPoolSize = [150] minimumPoolSize = [4] keepAliveTime = [300000] whenBlockedPolicy = [RUN] startUpSize = [4]
[INFO] Region [CENTRAL] Cache file root directory: C:\Users\Michael Ruffalo\.m2\repository\org\owasp\dependency-check-data\4.0\cache
[INFO] Region [CENTRAL] Set maxKeySize to: '1000000'
[INFO] Region [CENTRAL] Indexed Disk Cache is alive.
[INFO] initialized MemoryCache for POM
[INFO] Constructed cache with name [POM] and cache attributes [ useLateral = true, useRemote = true, useDisk = true, maxObjs = 0, maxSpoolPerRun = -1, diskUsagePattern = UPDATE, spoolChunkSize = 2 ]
[INFO] No cache event logger defined for auxiliary [jcs.auxiliary.ODC]
[INFO] Using standard serializer [org.apache.commons.jcs.utils.serialization.StandardSerializer@12c76d6e] for auxiliary [jcs.auxiliary.ODC]
[INFO] Region [POM] Cache file root directory: C:\Users\Michael Ruffalo\.m2\repository\org\owasp\dependency-check-data\4.0\cache
[INFO] Region [POM] Set maxKeySize to: '1000000'
[INFO] Region [POM] Indexed Disk Cache is alive.
[INFO] initialized MemoryCache for NODEAUDIT
[INFO] Constructed cache with name [NODEAUDIT] and cache attributes [ useLateral = true, useRemote = true, useDisk = true, maxObjs = 0, maxSpoolPerRun = -1, diskUsagePattern = UPDATE, spoolChunkSize = 2 ]
[INFO] No cache event logger defined for auxiliary [jcs.auxiliary.ODC]
[INFO] Using standard serializer [org.apache.commons.jcs.utils.serialization.StandardSerializer@46702c26] for auxiliary [jcs.auxiliary.ODC]
[INFO] Region [NODEAUDIT] Cache file root directory: C:\Users\Michael Ruffalo\.m2\repository\org\owasp\dependency-check-data\4.0\cache
[INFO] Region [NODEAUDIT] Set maxKeySize to: '1000000'
[INFO] Region [NODEAUDIT] Indexed Disk Cache is alive.
[INFO] Parsed regions [CENTRAL, POM, NODEAUDIT]
[INFO] Finished configuration in 96 ms.
[INFO] Checking for updates
