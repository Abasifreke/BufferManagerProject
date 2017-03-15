LIBPATH   = /eecs/dept/course/2016-17/W/4411/bufmgr/lib/bufmgrAssign.jar
CLASSPATH = $(LIBPATH):
JAVAC     = /eecs/local/bin/javac -classpath $(CLASSPATH)
JAVA      = /eecs/local/bin/java  -classpath $(CLASSPATH)

PROGS = together

all: $(PROGS)

db:DB.java
	$(JAVAC) DB.java

together:*.java
	$(JAVAC) *.java

xx:
	jar tf $(LIBPATH)

clean:
	\rm -f *.class *~ \#* core 
