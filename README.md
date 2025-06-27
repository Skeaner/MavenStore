# Skeaner-MavenStore
缓存自建仓库, 防止jitpack抽风 , 仓库地址 https://gitee.com/skean/MavenStore/raw/main/

gradle : maven { url "https://gitee.com/skean/MavenStore/raw/main/" }


gradle.kts : maven { url =uri("https://gitee.com/skean/MavenStore/raw/main/") }
