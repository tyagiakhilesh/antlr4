export CLASSPATH=<path/to/antlr-complete-jar>:.:$CLASSPATH
alias antlr4='java -jar <path/to/antlr-complete-jar>'
alias grun='java org.antlr.v4.gui.TestRig'

antlr4 <grammar file>
java *.java
java Main
