#Tugas khusus Gradle dan add libraries

Membuat Gradle sederhana dan menjalankan perintahnya lalu dorong ke GitHub.

##Cara kerjanya

1. Buat proyek Gradle sederhana dengan kode :
   task greetingTask(){
   doLast{
   String nama = project.hasProperty('nama')? project.property('nama'):'Gradle User'
   println "Hello,$nama!Welcome to Gradle World!"
   
2. Print dengan pesan ucapan dengan menjalankan perintah "./gradlew greetibgTask -Pnama=YourName"

3. Dorong proyek ke GitHub dengan perintah :
   git init
   git add .
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/Hmdfdjr/BelajarGradleJayjay.git
   git push -u origin main

##Tools yang di pakai :
- Language : Java
- Build System : Gradle
- JDK : 21
- Gradle DSL : Groovy
   
   








