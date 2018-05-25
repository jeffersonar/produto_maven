#ESTUDANDO MAVEN
projeto desktop java maven

<br/>
##Comando cria um projeto simples em mvn
mvn archetype:generate -DartifacctId=produtos -DgroupId=br.com.alura.maven -DinteractiveMode=false -DarchetypeArtifacId=maven-
archetype-quickstart
<br/>
<br/>
##compilar
mvn compile
<br/>
##testa
mvn test
<br/>
##relatorio de teste
mvn surefire-reports:report
<br/>
##relatorio de teste pmd:pmd
mvn pmd:pmd
#verificar validações
mvn pdm:check
#verifica todas as fases
mvn verify

##limpar target
mvn clean
<br/>

#opções
-o offline
ex. mvn -o teste