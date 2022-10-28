JC = javac

all:	Main.class ServerThread.class SendResponse.class MyURLDecoder.class Util.class

Main.class:	Main.java
	$(JC) $<

ServerThread.class:	ServerThread.java
	$(JC) $<

SendResponse.class:	SendResponse.java
	$(JC) $<

MyURLDecoder.class:	MyURLDecoder.java
	$(JC) $<

Util.class:	Util.java
	$(JC) $<

clean:
	rm *.class

PHONY: all
