# ESTUDANDO MAVEN
projeto desktop java maven

## Comando cria um projeto simples em mvn
mvn archetype:generate -DartifacctId=produtos -DgroupId=br.com.alura.maven -DinteractiveMode=false -DarchetypeArtifacId=maven-
archetype-quickstart
<br/>
<br/>
## compilar
mvn compile
<br/>
<br/>
## testa
mvn test
<br/>
<br/>
## relatorio de teste
mvn surefire-reports:report
<br/>
<br/>
## relatorio de teste pmd:pmd
mvn pmd:pmd
<br/>
<br/>
## verificar validações
mvn pdm:check
<br/>
<br/>
## verifica todas as fases
mvn verify
<br/>
<br/>
## limpar target
mvn clean
<br/>
<br/>
## opções
-o offline
ex. mvn -o teste
