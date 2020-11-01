pipeline {
   agent any

   parameters {
      choice(choices: '''20.4
                         20.3
			 20.2
			 20.1''', description: '', name: delta_version)
   }

   stages {
     stage ("test") {
        steps {
	  sh " echo hello!!!"
	}
     }
   }
}
