# Skeaner-MavenStore
缓存自建仓库, 防止jitpack抽风 , 仓库地址 https://raw.githubusercontent.com/Skeaner/MavenStore/main/

gradle : maven { url "https://raw.githubusercontent.com/Skeaner/MavenStore/main/" }			
gradle.kts : maven { url =uri("https://raw.githubusercontent.com/Skeaner/MavenStore/main/") }