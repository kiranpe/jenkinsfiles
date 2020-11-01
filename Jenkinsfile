properties([[$calss: 'ParameterDefinitionProperty', parameterDefinitions: [
[$class: 'ChoiceParameterDefinition', choices: ['20.4', '20.3', '20.2', '20.1'], description: '', name: 'delta_version'],
[$class: 'ChoiceParameterDefinition', choices: ['DIT', 'SIT', 'UAT', 'PreProd'], description: '', name: 'Target_Environment']
]]])

pipeline {
   agent any

   stages {
     stage ("test") {
        steps {
	  sh " echo hello!!!"
	}
     }
   }
}
