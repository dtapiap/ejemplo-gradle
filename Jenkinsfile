library ('pipeline')
// agregue la herramienta que  desea compilar Gradle o Maven
//  ingresar los stages  separados por ";" ( punto y coma ) VACIO se ejecutan todos
// 'build;'sonar';'upload_nexus''download_nexus','run_jar': 'stageRunJar','curl_jar': 'stageCurlJar'
    def varTOOLS = "Gradle"
    def varStages = "pico;ctm"
ejecucion.call(${varTOOLS},${varStages})
