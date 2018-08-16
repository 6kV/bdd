# bdd

### Principes

 + Conversations & Collaborations
 + Three Amigos
 + Specifications par l'exemple
 + Ubiquituous Language
 + Automatisation
 + Documentation Vivante
 
 Hierachie de Tags
 Utiliser l'impératif pour décrire le scénario
 Les tags peuvent avoir une description métier
 On peut filtrer par Tags, scenario, plusieurs tags, par Feature
 on peut avoir des piéces jointes aussi
 
 Créer un tag lui même annoté par un tag (@IsTag) -> à checker
 SCenario Test -> classe qui permet de partager des données entre le Given/When/Then
 
 Une classe qui contient des given ou when ou then est une classe Stage
 SELF c'est un alias de this() : permet à Jgiven de chainer les appels au niveau de la dsl
 
 @ProvidedScenarioState : état partagé entre le given when then
 
 @ScenarioRule
 @BeforeStage
 @AfterStage
 
 @ExpectedScenarioStage
 
 @Quoted
 @Table
 
 currentStep.addAttachement
