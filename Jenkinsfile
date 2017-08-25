node(‘NODE’){
  git url: 'https://agile.richemont.com/bitbucket/scm/sap/cms-car.git'
  def mvnHome = tool 'M3'
  env.PATH = "${mvnHome}/bin:${env.PATH}"
  sh 'mvn -B clean install'
}
