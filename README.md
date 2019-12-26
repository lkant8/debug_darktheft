# debug_darktheft
# To get a Git project into your build:
  # gradle
Step 1. Add the JitPack repository to your build file

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.darktheft:debug_darktheft:Tag'
	}
  
  [![](https://jitpack.io/v/darktheft/debug_darktheft.svg)](https://jitpack.io/#darktheft/debug_darktheft)
  
  # Maven
  Step 1. Add the JitPack repository to your build file
  
  <repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
  
  Step 2. Add the dependency
  
  <dependency>
	    <groupId>com.github.darktheft</groupId>
	    <artifactId>debug_darktheft</artifactId>
	    <version>Tag</version>
	</dependency>
  
  
    Step 1. Add the JitPack repository to your build file
  
  Add it in your build.sbt at the end of resolvers:

 
    resolvers += "jitpack" at "https://jitpack.io"
        
    
Step 2. Add the dependency

	
	libraryDependencies += "com.github.darktheft" % "debug_darktheft" % "Tag"
  
  
  
     Step 1. Add the JitPack repository to your build file
  
  Add it in your project.clj at the end of repositories:

 
    :repositories [["jitpack" "https://jitpack.io"]]
        
    
Step 2. Add the dependency

	
	:dependencies [[com.github.darktheft/debug_darktheft "Tag"]]	
  
  
  [![](https://jitpack.io/v/darktheft/debug_darktheft.svg)](https://jitpack.io/#darktheft/debug_darktheft)
  [![](https://jitpack.io/v/darktheft/debug_darktheft.svg)](https://jitpack.io/#darktheft/debug_darktheft) [![](https://jitpack.io/v/darktheft/debug_darktheft.svg)](https://jitpack.io/#darktheft/debug_darktheft)
