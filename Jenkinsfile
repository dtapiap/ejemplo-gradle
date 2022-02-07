library ('pipeline')

 environment {

// agregue la herramienta que  desea compilar Gradle o Maven
        varTOOLS = 'Gradle'
//  ingresar los stages  separados por ";" ( punto y coma ) VACIO se ejecutan todos
// 'build;'sonar';'upload_nexus''download_nexus','run_jar': 'stageRunJar','curl_jar': 'stageCurlJar'        
        varStages= ' '     
    }
ejecucion.call(${varTOOLS},${varStages})
